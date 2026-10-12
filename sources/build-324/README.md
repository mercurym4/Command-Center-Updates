# Command Center corresponding release source

This package accompanies the matching Command Center development APK. Verify
`sha256sum -c SHA256SUMS` before extraction. `source-revisions.txt` identifies the
application and all five pinned upstream revisions. Complete upstream archives,
their notices and the mGBA RTC patch are supplied with the application snapshot.
The development repository, history, private signing key, sender credentials,
workflow secrets and internal project-management records are not distributed.
There are no commercial game ROMs or proprietary BIOS files.

## Build the pinned source

Use JDK 17, Gradle 8.13, Python 3, Git, Android platform 36, Build Tools 36.0.0,
NDK 27.2.12479018 and CMake 3.22.1. Set `ANDROID_HOME` to your SDK and:

    export ANDROID_NDK_HOME="$ANDROID_HOME/ndk/27.2.12479018"

Extract `command-center-source.tar.gz`, then enter `command-center/`. For the
normal online build, leave the companion upstream archives unextracted and run:

    bash scripts/build-fceumm.sh
    bash scripts/build-snes9x.sh
    bash scripts/build-genesis.sh
    bash scripts/build-mgba.sh
    bash scripts/prepare-rcheevos.sh

These scripts fetch exact pinned Git revisions. Network access to the upstream
repositories, Google's Android/Maven repositories and Maven Central is required.
The mGBA script applies its verified RTC extension automatically; do not apply
the companion patch again in this procedure. The supplied Android client
`app/google-services.json` enables the release's generated Firebase resources;
it contains no sender authorization. Omitting it changes push configuration.

Generate your own development signing key:

    mkdir -p config
    keytool -genkeypair -storetype JKS \
      -keystore config/commandcenter-debug.jks \
      -storepass commandcenter -keypass commandcenter \
      -alias commandcenter-debug -keyalg RSA -keysize 2048 -validity 10000 \
      -dname "CN=Local Source Rebuild, O=Local Development, C=US"

This key is for your local rebuild only. It is not the distributed app's key, so
your APK cannot update an installation signed by the existing distribution key.
Set `GITHUB_RUN_NUMBER` to the accompanying APK's versionCode for the matching
version identifier, then run:

    gradle testDebugUnitTest assembleDebug

The APK is `app/build/outputs/apk/debug/app-debug.apk`. An unsigned release variant
can be built with `gradle assembleRelease`; it disables development updates.
Private production signing credentials are not required for that unsigned build.

## Inspect or modify the companion source

Extract fceumm, snes9x2005, genesis-plus-gx and mgba source archives into
`command-center/vendor/`, and rcheevos into `command-center/.external/`. Each
archive already contains its final directory prefix. The mGBA archive is pristine
upstream source; apply the supplied patch once from `vendor/mgba/`:

    patch -p1 < /path/to/distribution/mgba-command-center.patch

The tarballs have no Git metadata. Do not run the unchanged clone-based scripts
over these populated archive directories. For a modified extracted source build,
use the native NDK/CMake commands in the supplied scripts without their Git
clone/fetch/checkout sections. A turnkey offline rebuild is not claimed.

Keep complete upstream source, licenses and copyright notices with any
redistribution. See `command-center/docs/CORE_LICENSING.md` and
`command-center/vendor/README.md`. No signed byte-for-byte APK reproduction is
claimed: private signing keys, environment and generated resources affect bytes.
