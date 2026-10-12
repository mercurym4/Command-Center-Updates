# Command Center patch history

Patch numbers match installed build numbers. Publication dates are UTC. History begins with the first surviving published release, Patch 35; gaps are unreleased builds. Historical changes are recovered source summaries.

## Patch 317 — 2026-10-12

### Added

- Numbered patch notes tied to the installed build.
- An offline Patch history view with dates and recovered changes for every recorded release, starting at Patch 35.

### Improved

- The update popup shows only the current patch. Older changes are grouped under their original patch numbers instead of appearing as new features.

## Patch 312 — 2026-10-11

- Added complete artwork catalogs for Game Boy, Game Boy Color and Game Boy Advance.
- Fixed Stretch gameplay padding above the image, including the camera-cutout area.
- Fixed library refresh stopping when an artwork catalog is missing; existing and manual covers are preserved.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/75b03643e109b272cf3f60891f8c11c9bb8a0347/latest.json

## Patch 309 — 2026-10-11

- Added Game Boy, Game Boy Color and Game Boy Advance playback with distinct system cards and handheld controls.
- Added handheld battery saves, save states and supported cartridge-clock persistence.
- Fixed handheld startup/lifecycle crashes and clipped GBA controls.
- Improved achievement-client regression reliability.
- Added matching corresponding-source downloads alongside each development APK.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/a7f237df643c26d25ed55ef9cf7a1a8121fceef0/latest.json

## Patch 285 — 2026-10-10

- Add dedicated Achievements tab and verify Google Play release candidates
- Prepare signed Play release workflow, source archives and store materials
- Fix Scaffold navigation lambda closure
- Pin the native toolchain and check actual RELRO writable-data overlap
- Keep the full Achievements label visible on narrow navigation
- Scope navigation overflow assertion to the tab label
- Set compact navigation line height and verify settled tab layout first
- Give the Achievements label a bounded width beyond navigation padding

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/919f82fdbf6d0d6a457c0513e1ded03e8836fd79/latest.json

## Patch 277 — 2026-10-10

- Recover transient RetroAchievements reads and service paused clients

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8ebd41a6ce287e5abd87607ceadb0bf09f0e6394/latest.json

## Patch 276 — 2026-10-10

- Enable notification categories by default and request Android permission at startup
- Automatically upgrade untouched legacy notification categories for banners
- Guide notification setup after upgrade with permission and category settings actions

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/17a9d99286b4eed13428faa30114f176a7877817/latest.json

## Patch 273 — 2026-10-10

- feat: show service-earned RetroAchievements history separately from previews

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/040a6d8182c2f18b0a939221e99f09f7bd33cf1b/latest.json

## Patch 272 — 2026-10-09

- Activate Firebase client and validate live sender before publication

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/fd8ae0a2d7a928e0e7536b6a1f828ffd89c983fe/latest.json

## Patch 270 — 2026-10-09

- Make translucent controls visibly lighter with faint fills and outlines
- Remove the portrait control band and float outlined controls over the full game frame
- Keep floating control labels readable over bright game graphics
- Verify floating portrait controls against rendered game pixels

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/2ef9aef04037acbb3784c5882c9caddf0f65bf4b/latest.json

## Patch 266 — 2026-10-09

- Restart and recover game audio after turbo and interrupted playback

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6f97887fa8a1f837d65a6cbc1099c8dd1fa278d3/latest.json

## Patch 265 — 2026-10-09

- Restore portrait R2 fast-forward and the SNES face-button diamond
- Make gameplay controls and the floating Menu pill translucent
- Increase gameplay touch-control dimensions by five percent
- Keep enlarged SNES face buttons in a compact diamond with circular touch regions
- Expose full touch-button bounds for accessibility and size verification
- Label full circular touch controls explicitly in accessibility

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/ca0d8460075898ffb0e5200acf20a7edee67b168/latest.json

## Patch 259 — 2026-10-09

- Let the Menu pill float without reserving a portrait header

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7dd5485c73d116fd34a9c96425df1bd5ed13b7b4/latest.json

## Patch 258 — 2026-10-09

- Compact portrait touch controls and reclaim gameplay space

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/59fb883398e75039a9a5bc0a90c9b03e3636cbef/latest.json

## Patch 257 — 2026-10-09

- Preserve complete portrait game frames and keep touch controls below the image
- Correct newline formatting in portrait scaling update notes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6183897964c7890b86fe03c6a6d830d9baefbfd1/latest.json

## Patch 255 — 2026-10-08

- Evaluate RetroAchievements gameplay previews with official memory maps and saved runtime progress
- Keep libretro ABI declarations compatible with the C memory adapter
- Expose the local libretro header to frontend memory adapter includes
- Keep spectator previews separate from service account point totals
- Capture achievement progress evidence on its themed surface

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/734def0838b593c2f342f3109000d9a4ba90fe98/latest.json

## Patch 249 — 2026-10-08

- Add local player profiles, separate stats and Command Center milestone achievements

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/49ebf0bf93512e5c3233e54aff80efbca6c01b1b/latest.json

## Patch 248 — 2026-10-08

- Organize Systems console menus and add dedicated achievements with official badges

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/85ff75d0645d686d097c504b6547e3378d527296/latest.json

## Patch 247 — 2026-10-08

- Connect RetroAchievements accounts and browse official game sets
- Fix achievement UI test lifecycle and SDK version expectations

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/1358876f428347c17490810c35d57f7ad80a80e2/latest.json

## Patch 245 — 2026-10-08

- Start official RetroAchievements ROM identity and improve notification inbox controls
- Provide libretro headers to the pinned RetroAchievements adapter
- Exclude optional memory adapter until frontend memory maps are integrated
- Scope unread badge checks to the Settings and notification dialog controls
- Find unread labels in the unmerged button semantics tree

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7c030f73c77624055c25f329eef2cdac14e43aec/latest.json

## Patch 240 — 2026-10-07

- Add opt-in Firebase notification client, announcement inbox and conditional update push publishing
- Validate optional push publisher identity and document token permissions
- Use conditional Python OAuth sender instead of an additional workflow action
- Refresh an open notification inbox when new messages arrive

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/c990978bad1922c9ea5af17af1023690a6b2ad4c/latest.json

## Patch 236 — 2026-10-07

- Add optional gameplay performance panel with actual emulated speed and audio diagnostics
- Match selected display mode label in gameplay diagnostics verification
- Show scrollable installed update notes once per build and reopen them from Settings
- Keep restored update-notes visibility scoped to the installed build

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3ea1d4c26fb547d88341c2bce354d3dbe68772eb/latest.json

## Patch 232 — 2026-10-07

- Repair missing or damaged downloaded covers on refresh and distinguish artwork catalog misses from failed downloads

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5f3397d305bb12d79c106861790fb9a2aafa8e7e/latest.json

## Patch 231 — 2026-10-07

- Recover readable ROM folders after provider failures and reduce repeated large-library sorting
- Scope large-library search assertions to game cards rather than editable search text

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6eeaa0ef8defc2e13c54147d4ac3cd66aff51343/latest.json

## Patch 229 — 2026-10-06

- Checkpoint completed artwork through interrupted foreground scans and bound bulk import updates

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/67afc4fb92c00071dec8ed20803adac3d7a58303/latest.json

## Patch 228 — 2026-10-06

- Fit full custom backgrounds across Fold screen changes with persistent fit and fill controls

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/db16cafba59b4b1992d5b2b4a5d289dcbca2ab8c/latest.json

## Patch 227 — 2026-10-06

- Persist cartridge battery saves and add verified in-game backup restore
- Declare libretro battery memory ABI in frontend header
- Keep full load-time SRAM capacity when Genesis reports modified byte ranges
- Dismiss emulator launcher ANR before real controller injection and screenshot capture

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/da175a15a4e6e3596a3b7cdfb9ff12fc013dd18d/latest.json

## Patch 223 — 2026-10-05

- Add per-system controller mappings, dead zones and live diagnostics
- Wait for paused menu before comparing diagnostic native state
- Fix connected gamepad enumeration for Android device ID arrays

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7dbab140441fe37904d7036e3243e11413720dd5/latest.json

## Patch 220 — 2026-10-05

- Add game-screen previews to save states and preserve them in backups

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/362b6ff8b2ee6f7f5b91edcf364b70597bb14de7/latest.json

## Patch 219 — 2026-10-05

- Reject deeply nested backup metadata before JSON parsing and verify escaped save names

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/1a3eaecbf0bf58900a9b3f73366983eb939199ad/latest.json

## Patch 218 — 2026-10-05

- Add per-game save-state backups and validated restore without overwriting existing snapshots
- Let save lists shrink around backup controls and keep empty-state dialogs compact

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/001fa1bc31f5cc433a252c556dbd3d4449d31ac6/latest.json

## Patch 216 — 2026-10-05

- Add touch haptics and selectable turbo up to 20x with measured gameplay speed
- Keep default save placeholder visible before focus and allow idle between overloaded turbo batches

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/fefa537f151a0d3aa97295ab2b48056168fe5b13/latest.json

## Patch 214 — 2026-10-05

- Fix audio frame pacing and retain partial PCM writes; show default save name

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/78619350e8d7831f92cf8721c367e5ee8a41cc0f/latest.json

## Patch 213 — 2026-10-04

- Prompt for save-state names before creation and clarify saved-state loading
- Keep save-name prompt scrollable when the keyboard reduces available height
- Focus the save-name editor and verify real keyboard input in player test
- Recover only the emulator Quickstep ANR overlay during player verification
- Target the editable save-name node instead of its label wrapper in native UI test

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5cb36a8638d1414b5efeedc14eb1610cca626e8a/latest.json

## Patch 208 — 2026-10-04

- Add persistent save-state names and compact accessible list actions
- Keep long-name UI test fixture within supported 64-character limit
- Disambiguate rename confirmation button from editable field in UI verification

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7f0e4d77f3720caba24e0a8baece6ec8b779a491/latest.json

## Patch 205 — 2026-10-04

- Apply retro muscle mascot and command station adaptive launcher icon

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7c541de522d3f953f562036b5a54bd1494a97a86/latest.json

## Patch 204 — 2026-10-04

- Add per-game multiple save states with dated list, selection and individual deletion
- Retire legacy migration source when deleting an existing save
- Verify selected save restoration against the core's normalized load result

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5d13279ff9a5781c19fa059edaa54533de4aaf05/latest.json

## Patch 201 — 2026-10-04

- Automatically refresh saved ROM folders and missing artwork on foreground entry
- Expose per-system library links and reset stale filters when browsing a console

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/fdffe8c655f92a90d6a04181b441f30baeb174b0/latest.json

## Patch 199 — 2026-10-04

- Match reported SNES artwork aliases and GoodTools Europe/Japan regions

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/9cdf1efbc41352064cebcbf5060fd858b79f9c1a/latest.json

## Patch 198 — 2026-10-04

- Resolve artwork using real catalogs with backup downloads and metadata-safe merges
- Verify artwork backup host with a live forced-failover download
- Check the artwork accessibility label using the full imported ROM title
- Keep artwork test void and wait for resumed player focus before controller dispatch

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/4244b624285aba860d861b0b54c8de1c0acf469e/latest.json

## Patch 194 — 2026-10-04

- Polish Genesis cover controls and capture settled dialog screenshots

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/0245299c7e0151a17c434d7803b57a41f389af9d/latest.json

## Patch 193 — 2026-10-04

- Add Genesis cartridge playback with six-button controls and native regression coverage
- Verify Genesis system dashboard, setup and controller guidance

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/1bd9e6f5ece673c2d44f1b7667149194db815d64/latest.json

## Patch 191 — 2026-10-04

- Handle analog controllers and pause gameplay safely across menus and background transitions
- Keep fast-forward state current inside the running emulation loop
- Verify continuously rendering player through live Android UI actions
- Traverse Compose accessibility children in live player tests and capture failure evidence
- Dismiss Android fullscreen onboarding in fresh CI emulator before player verification
- Handle delayed system fullscreen tutorial during live player UI verification

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b0af69441a6248cd05696fdb5f9fa56a1a637101/latest.json

## Patch 185 — 2026-10-04

- Separate game browsing from console readiness and setup
- Add ranked system playtime, podium stars, controller options and per-console display settings

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/0a44c587f9dc7fadcc2d37b6a8756be7c8afacea/latest.json

## Patch 183 — 2026-10-04

- Consolidate document aliases and show added dates and activity on game cards
- Preserve save states across document alias consolidation

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/ae43aeeaa1823de368d8b777fb9cef9b52186f9f/latest.json

## Patch 181 — 2026-10-03

- Add pinned SNES playback, system-aware controls and native core-switch regression tests
- Account for SNES RGB565 green quantization in native input regression

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/748ccfab4ef00c0a6da69ac7ebca01a389442368/latest.json

## Patch 179 — 2026-10-03

- Compact Home banner and responsive Library toolbar without hiding game stats
- Use DpRect edges for responsive toolbar and banner size assertions

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3700a04c27c171ce33dffe720cef7bb4ffdaad7b/latest.json

## Patch 177 — 2026-10-03

- Restore visible playtime, launches and last played on Home game previews

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/c64f57e63927831d0401a2e9081d2ad06330e222/latest.json

## Patch 176 — 2026-10-03

- Overhaul Home, Library and Systems with responsive Fold layouts and verified publishing gates
- Fix emulator disk exhaustion, add console silhouettes and verify Fold resize and APK identity
- Reserve runner disk space required by Android emulator userdata image
- Preserve UI screenshots after test uninstall and correctly validate native APK ABI; protect controls over bright backgrounds
- Export screenshot bytes through UiAutomation stdin and verify complete file writes
- Publish verified responsive launcher overhaul with immutable APK update URLs

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/63f3cf3b90e66a1a480047bde58db63a14ebd57c/latest.json

## Patch 170 — 2026-10-03

- Visual overhaul pass: compact unified banners and artwork cards, reclaim Home and Library space

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/01f5678dadd18d04e94413504955079f2bd05447/latest.json

## Patch 169 — 2026-10-03

- Compact Systems preview cards and place Library navigation before game shelf

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/395ca33ae2486ba385a6f53fc0b41511308f4d56/latest.json

## Patch 168 — 2026-10-03

- Add compact horizontal game previews to each Systems console card

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6f7aec9835f8d6b65edc22cef88e474e87eb9300/latest.json

## Patch 167 — 2026-10-03

- Restore compact horizontal game previews under each Library console

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b4c62afa59247b955f0299071add7b30fd886486/latest.json

## Patch 166 — 2026-10-03

- Make Library console collections compact; remove duplicate preview game shelves

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/e3437d891133c7e5f29cd949861e93832a592050/latest.json

## Patch 165 — 2026-10-03

- Remove duplicate game heading from focused Library toolbar

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/d0a19dd1e93e30748a4a3868fb541ea446cdd1f4/latest.json

## Patch 164 — 2026-10-03

- Fix Library collections vertical scrolling and show game results only in focused library

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/17b4b3eedb8833241ae260f38fe420207dc2d3a5/latest.json

## Patch 163 — 2026-10-03

- Add compact Library search and favorites-only browsing within console collections

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b2f194a10e24b59a8a1005b505f744aa42d989be/latest.json

## Patch 162 — 2026-10-03

- Make Systems console management only; remove duplicate game shelves

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/ae8b54a54f29592e3d8a79bd999313a13cfc9193/latest.json

## Patch 161 — 2026-10-03

- Declutter Home Favorites and Systems; show imported consoles only and unify game cards

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7d7e844c7db324c82bba791e1023442991d9e91a/latest.json

## Patch 160 — 2026-10-03

- Fix Fold library viewport: compact focused browsing header and hide maintenance controls
- Prioritize game browsing: collapse Library filters, compact toolbar and remove oversized grid metadata

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/37689a7b3cd9d86bdd600eec72da0f83d63367f8/latest.json

## Patch 158 — 2026-10-03

- Premium overhaul: unified cinematic cover tiles, console identity, streamlined collections, accurate global hero and recency
- Premium overhaul: compact brand masthead, emphasized navigation, cinematic library grid
- Fix stale Recent card block left after unified premium tile migration

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/f701a659bc35fa0a8a44906074bc07872da94f3c/latest.json

## Patch 155 — 2026-10-03

- Make View library open focused game list instead of reselecting active console

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/24bc4fe249129427b2c89f52312d6f55d154ed32/latest.json

## Patch 154 — 2026-10-03

- Match Favorites and Recent section backdrops to compact command deck header

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/460527670868e57b2823529e1b4b4dc3cc6a4edc/latest.json

## Patch 153 — 2026-10-02

- Improve navigation hierarchy with bold high-contrast section headers and active-system breadcrumbs

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/f27dccf488da86f473a7ea5d3f7d6b95d139e062/latest.json

## Patch 152 — 2026-10-02

- Premium phase 2: cohesive console identity banners and adaptive collection styling

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/97677dc3204d4f5e024a84d7073cf000b82ccc5a/latest.json

## Patch 151 — 2026-10-02

- Premium UI phase one: cinematic featured hero and distinct navigation icons
- Restore console collection browsing directly in Library with cover cards and system filtering
- Restore full Systems-style console sections and game shelves within Library
- Unify system filtering across Home collections Favorites and Library sorting
- Apply shared console selection to Home shelf rendering and Favorites filter visibility
- Add missing Compose material icon dependency to fix build

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5f68c0425f8758f57bf4feb77a1df3d6caf524ec/latest.json

## Patch 145 — 2026-10-02

- Fix narrow Fold library list metrics and give Systems dedicated console collections
- Always expose Library console filter even with only one imported system

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6f1f89cd34ec9b33d5575bd583ece6ab9c95c848/latest.json

## Patch 143 — 2026-10-02

- Build console-grouped Systems tab with NES playable status and future console sections
- Align gameplay statistics across Systems and Library and rank Played by duration
- Add ROM import dates beside game activity metrics in all views

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b1a5aa60718735793a6f86a4d2a328d9fa11518b/latest.json

## Patch 140 — 2026-10-02

- Display gameplay duration, launches and last-played on home Recent cards
- Show playtime, launches and last played in both Favorites card layouts

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6b17370a758dfec75d50307cc9beea635c2378e4/latest.json

## Patch 138 — 2026-10-02

- Expose short recorded sessions in library list instead of displaying zero minutes
- Persist last-played timestamps alongside live gameplay and background time

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/88935894d8d402ba773b6e1046b92581da909fdf/latest.json

## Patch 136 — 2026-10-02

- Rank Most Played by total playtime throughout game views
- Show launch count metric in library list and grid

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b3ef72b36603c75fcbeac6b4e3baa07a61e72daf/latest.json

## Patch 134 — 2026-10-02

- Avoid stale cached manifests during in-app update checks
- Recheck app updates whenever Command Center returns to foreground

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/29683c2ae4a6bb4618ca841d54d16740fb7f890f/latest.json

## Patch 132 — 2026-10-02

- Display accurate short and long playtime labels in library grid

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/259792daa879283b6401df2a95e69ab5cd90ff99/latest.json

## Patch 131 — 2026-10-02

- Balance library grid across phone and unfolded tablet layouts

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/27c84bfdd5f3cbf333156694aafdb467e98e5ff3/latest.json

## Patch 130 — 2026-10-02

- Add persistent adaptive cover grid and list toggle to game library

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/dab48ccc5f5bfff4b0b185ef087dcf7591f88c25/latest.json

## Patch 129 — 2026-10-02

- Give library more vertical space with compact screen-specific header

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/56534716f5eff3df1685302ef5fadd0bfc2631e2/latest.json

## Patch 128 — 2026-10-02

- Compact library cards and keep game list within scrollable viewport

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7b3545b6ad3f377674fc4a14a27f624fc40e1e35/latest.json

## Patch 127 — 2026-10-02

- Start premium library overhaul with responsive controls and library summary
- Add interactive sorting controls to premium game library

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/14965d5d0f92d5eaf7a0d4ba159dabc3349fe70f/latest.json

## Patch 125 — 2026-10-02

- Release publication recorded; no separately documented product change in this source interval.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3027e2dcd4af1e00dc6a256d5716fbbfde11aaff/latest.json

## Patch 124 — 2026-10-02

- Automatically scan newly imported ROMs for artwork while preserving library metadata
- Keep automatic artwork scan alive when scan status changes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/0d4cc631999b8fbc2f30993b90d73fbe6c8edce2/latest.json

## Patch 122 — 2026-10-01

- Replace hanging artwork catalog scan with bounded direct cover lookup

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/cef1f9068d95124145041bc8081f2f6ab9181490/latest.json

## Patch 121 — 2026-10-01

- Report artwork catalog failures and scan progress
- Display artwork catalog loading and matching status
- Persist launch counts and preserve history when rescanning
- Update recently played at launch and rank most played by sessions
- Autosave game playtime every five seconds during active sessions
- Autosave gameplay each second and flush on app background
- Declare lifecycle Compose dependency for gameplay tracking

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/a3da0c93c485b3882c7d28196c097ce411d027f3/latest.json

## Patch 113 — 2026-10-01

- Add automatic Libretro game cover matcher and downloader
- Add automatic artwork scanning button to library

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/9bc82c6a993de998ad55e7da7e858d7924566740/latest.json

## Patch 111 — 2026-10-01

- Show updater progress, installation permissions and download errors

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3e9b454ed3c6b6870e154950ca6363e6f151d8b4/latest.json

## Patch 110 — 2026-10-01

- Prioritize simultaneous touch gameplay input over global swipe gesture
- Use explicit pointer hold loop for touch controls
- Fix Compose pointer input compilation error

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/0bcda30579e39123ec3c15608611205c6b3d119d/latest.json

## Patch 106 — 2026-10-01

- Preserve Home and Settings scroll positions across navigation

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/00a388afa4740b50a94ab285ef459b513444fd2d/latest.json

## Patch 105 — 2026-10-01

- Constrain background slider and align darkness label

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/e5dff08c7220808215c6608e15a65a6f568f63d3/latest.json

## Patch 104 — 2026-10-01

- Compact Settings background selection and theme cards

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/ab26f354e95b8804af1f35274bd34a427d7445c4/latest.json

## Patch 103 — 2026-10-01

- Compact featured card and display clean game titles

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/2521208136e37e6b3f635c65326eff795bd6c484/latest.json

## Patch 102 — 2026-10-01

- Detect custom background luminance to select readable text

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6062dcde19a466cbe2e8452ba6791e2cf6f66770/latest.json

## Patch 101 — 2026-10-01

- Correct shared screen and Library card text contrast
- Fix Systems screen text contrast

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/d6c6b0ae797b982b23b4a2970cd001fedb1d58d0/latest.json

## Patch 99 — 2026-10-01

- Fix Settings headings and selected theme card text contrast

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/1424fbb644684b65074ec75e195e4075fd5a427f/latest.json

## Patch 98 — 2026-10-01

- Keep featured title clear of artwork and compact Home spacing
- Fix Recent heading contrast on custom backgrounds
- Tie Home typography colors to background and theme settings

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6ca474081f4bd09daaa39893fb88779e90de4e49/latest.json

## Patch 95 — 2026-10-01

- Improve Home contrast and contain featured artwork

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/635a6819bffb0924cfe7301b267c55ab97e73e9e/latest.json

## Patch 94 — 2026-10-01

- Clean up Home controls and fix background text contrast
- Streamline Home menus and redesign Library cards

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/2315334eaa2fde460a075f206a4702fc29bd1777/latest.json

## Patch 92 — 2026-10-01

- Add Favorites filters and Home collection sorting

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/f2b6088e269a230e6e63b6cb00b5965aa8725ffb/latest.json

## Patch 91 — 2026-10-01

- Persist game import dates across rescans

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/60f283cfeb214727e08c575398c6e08b7956411c/latest.json

## Patch 89 — 2026-10-01

- Fix settings scrolling and separate game art from backgrounds

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/4e2ff62eaf8878d6034dbf2bbbe0a54b8f9cce0a/latest.json

## Patch 88 — 2026-10-01

- Add selectable gaming background gallery

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/dc8abe8dd1ab11ac1d5f24bdedb832575b4cfbe7/latest.json

## Patch 87 — 2026-10-01

- Add persistent app background options

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7adf5cc8a054bb74dd6dc2020b0818e6b54d0a6b/latest.json

## Patch 86 — 2026-10-01

- Add persistent preset color themes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/642bd0c369443a32fcf6cb6d82fc468cbdd2c3c6/latest.json

## Patch 85 — 2026-10-01

- Upgrade Home with artwork hero and recent game cards

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/84a03311185e94312ff4cbee19409820887e4910/latest.json

## Patch 84 — 2026-10-01

- Add Grid and List views for Favorites

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/be9235cb3788fafa1ee361b6cf629643ce792c27/latest.json

## Patch 83 — 2026-10-01

- Make Home vertically scrollable so favorite metadata stays visible

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/e1d5259cd6283997476c479d0c8bca4282dcb9ec/latest.json

## Patch 82 — 2026-10-01

- Keep Favorites visible and show game metadata
- Repair Favorites home section layout

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/ff3e4940eb2c94cec086057e6a8036f6c31af8c2/latest.json

## Patch 80 — 2026-10-01

- Use Android photo picker for custom game artwork
- Fix photo picker request type
- Launch favorite games directly from Home

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/2a71a1f3fcf70fd2b6294dcdcaa0c1aeba6eedae/latest.json

## Patch 77 — 2026-10-01

- Expose favorites, custom artwork, and playtime in UI
- Add Compose image loading for custom game artwork

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5435de72947fa835e0fd7ac96b1deb63764d8d41/latest.json

## Patch 75 — 2026-09-30

- Add favorites custom artwork and playtime tracking
- Prevent stale builds from overwriting newer updates

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/0a2600ed3fab9f8dd2a3d81f24d1846820a9069b/latest.json

## Patch 74 — 2026-09-30

- Persist game personalization metadata
- Add favorites custom artwork and playtime tracking

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/b11a0ab351fe8fe0940d99f7449e9236fe698daa/latest.json

## Patch 73 — 2026-09-30

- Release publication recorded; no separately documented product change in this source interval.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3fed2ba5243db8454b44503565495e8ccbfd5b7e/latest.json

## Patch 72 — 2026-09-30

- Expand game records for favorites artwork and playtime

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/d65363a726bcfce3369267c0e24c908275bb1a04/latest.json

## Patch 71 — 2026-09-30

- Redesign home and library as gaming dashboard

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/864e75bfdc89197953dfcacce5f44fbbc28d83de/latest.json

## Patch 70 — 2026-09-30

- Polish in-game controls and save confirmation

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/a0c3800574f1466a61ba57018716ad9ca3214c35/latest.json

## Patch 69 — 2026-09-30

- Introduce Command Center visual identity

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/a7d1e03329706635e9728c2cfc972347328f3319/latest.json

## Patch 68 — 2026-09-30

- Add save-state confirmation dialog with timestamp

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/27625071da79c5e0627abe98da8e59367f7ca580/latest.json

## Patch 67 — 2026-09-30

- Show gameplay confirmation when loading state

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/1a04d9c5aea259d2ff3fdda4458c31351b7dbd14/latest.json

## Patch 66 — 2026-09-30

- Refine NES touch control spacing

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/577646deb0e1db47fdeee9135af8e24b67e85e28/latest.json

## Patch 65 — 2026-09-30

- Display installed build version dynamically

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8c059eb7297536a31dda33a613e45adbf0cb6060/latest.json

## Patch 64 — 2026-09-30

- Polish foldable NES control layout

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/7fce1429285084e3443c6f0f009580365966f5cc/latest.json

## Patch 63 — 2026-09-30

- Preserve gameplay across fold and orientation changes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8aae3ce831f5778997da18429f9bec26434905c4/latest.json

## Patch 62 — 2026-09-30

- Scale NES controls for compact displays

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/16939b32660a5e87ebc1792b3191c47a9a130f46/latest.json

## Patch 61 — 2026-09-30

- Finalize shoulder controls and R2 turbo binding

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6405eb2e7f8e01d3291c3cf98794e04addeae738/latest.json

## Patch 60 — 2026-09-30

- Publish post-59 updater validation build

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8681815d4fcb2f967f9fcd1ee6e14716d215b710/latest.json

## Patch 59 — 2026-09-30

- Mark build 59 updater validation

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/098cd29e233ed254392eda18a50f501a31860b45/latest.json

## Patch 58 — 2026-09-30

- Verify downloaded APK before installer handoff

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/f482c492ef5bf8809849e988ecc876b1c6ed4303/latest.json

## Patch 57 — 2026-09-30

- Use Android installer UI for development updates

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/3088cf86976a0d084203d4bec0229c66f5308425/latest.json

## Patch 56 — 2026-09-30

- Declare downloaded source for self update sessions

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8b1c8d4a76fea443be4d4900a9cb8277740a871d/latest.json

## Patch 55 — 2026-09-30

- Release publication recorded; no separately documented product change in this source interval.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/c782b4ffb31a7862fda4419897898ff45bb75d9d/latest.json

## Patch 54 — 2026-09-30

- Persist package installer results across app restart

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/dee31c544be59ede550588cc570a1dd73e9e8540/latest.json

## Patch 53 — 2026-09-30

- Polish in-game menu and edge swipe controls

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/26e709b0841d937942f4fa7095d02c10a9ba45ef/latest.json

## Patch 52 — 2026-09-30

- Add updater validation build marker

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/cdb9081c0341674c93d8e512c1ae8cedec0fec8b/latest.json

## Patch 51 — 2026-09-30

- Surface in-app update install status

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/57b88f58db9af8b8b1e5f75697d693b13766e7a7/latest.json

## Patch 50 — 2026-09-30

- Report package installer update results

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/5873004fb01308e69ec5b82410e3b3edcbe0c505/latest.json

## Patch 49 — 2026-09-30

- Polish in-game display menu transitions

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8cc9dad870d5ecc3a1f6634935c464023f62fb5d/latest.json

## Patch 48 — 2026-09-30

- Open in-game menu with horizontal swipe

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/c608f6f1fed77a7b01d2a0f261c788939dfd3e0b/latest.json

## Patch 47 — 2026-09-30

- Replace prototype player actions with game menu

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6324fd16d5b51ce7c6ae19b13a9ea8d44308252a/latest.json

## Patch 46 — 2026-09-30

- Add selectable emulator display modes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/e5d5fa6c1912f61aa0f9fc18db330b8e5b357709/latest.json

## Patch 45 — 2026-09-30

- Add persistent emulator display modes

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/de1fc2c4f9a2f54afae96e6c7b033b06405dff11/latest.json

## Patch 44 — 2026-09-30

- Release publication recorded; no separately documented product change in this source interval.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/e1408c94b1630df8450ebfb955455d535040596b/latest.json

## Patch 43 — 2026-09-30

- Scan multiple ROM folders safely

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/737003a7e4cb2237621fc5b00efd22aaf7c52e2a/latest.json

## Patch 42 — 2026-09-30

- Register update install status receiver
- Persist multiple ROM library folders

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8a8a128689163acace0ef3ba082872ac4e0545d5/latest.json

## Patch 41 — 2026-09-29

- Use PackageInstaller sessions for in-app updates
- Handle package installer update confirmation
- Register update install status receiver

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/6865e1f5bf0eca8f95367ae71ce4764ceeed7cd1/latest.json

## Patch 40 — 2026-09-29

- Release publication recorded; no separately documented product change in this source interval.

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/43c43a170d3388e0ba952795c154e4d9e820a71e/latest.json

## Patch 38 — 2026-09-29

- Add touchscreen shoulder trigger and stick controls

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/8f2fa3b833bb1e21b990a9fa7af8c92019f18f8b/latest.json

## Patch 37 — 2026-09-29

- Add hold R2 fast-forward for NES

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/732693676dbf082877487674954a461ae615c01e/latest.json

## Patch 36 — 2026-09-29

- Map full controller shoulder trigger and stick buttons

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/4a2f564c9a83b18d7e9c3afacfe122eb7d1747ad/latest.json

## Patch 35 — 2026-09-29

- First surviving published update-channel release; includes the initial development history below.
- Initialize README.md
- Initialize .gitignore
- Initialize settings.gradle.kts
- Initialize build.gradle.kts
- Initialize gradle.properties
- Add app/build.gradle.kts
- Add app/src/main/AndroidManifest.xml
- Add app/src/main/res/values/themes.xml
- Add app/src/main/java/com/commandcenter/app/emulation/EmulationEngine.kt
- Add app/src/main/java/com/commandcenter/app/MainActivity.kt
- Make game folder import functional
- Add local game library scanner
- Add recursive game library scanning
- Persist imported game library
- Restore saved library on startup
- Fix library initialization order
- Add docs/CORE_LICENSING.md
- Add app/src/main/java/com/commandcenter/app/emulation/EngineRegistry.kt
- Add app/src/main/java/com/commandcenter/app/emulation/nes/NesEngine.kt
- Add app/src/main/cpp/CMakeLists.txt
- Add app/src/main/cpp/commandcenter_native.cpp
- Add app/src/main/java/com/commandcenter/app/emulation/nativebridge/NativeEmulationBridge.kt
- Enable ARM64 native emulator build
- Add app/src/main/cpp/libretro.h
- Add app/src/main/java/com/commandcenter/app/emulation/nativebridge/NativeNesBridge.kt
- Add docs/NES_INTEGRATION.md
- Add .github/workflows/android.yml
- Implement guarded libretro NES JNI frontend
- Connect NES engine to native frontend and save states
- Add scripts/build-fceumm.sh
- Add vendor/README.md
- Add app/src/main/jniLibs/README.md
- Link native frontend with dynamic loader
- Build pinned NES core in Android CI
- Dynamically load bundled FCEUmm core
- Make Android CI self-contained
- Implement app/src/main/java/com/commandcenter/app/emulation/input/NesInput.kt
- Implement app/src/main/java/com/commandcenter/app/emulation/nativebridge/NativeNesBridge.kt
- Implement app/src/main/java/com/commandcenter/app/ui/player/NesPlayerScreen.kt
- Add NES framebuffer and controller callbacks
- Launch NES games from library
- Clean NES launch screen integration
- Fix Android SDK setup and publish debug APK artifact
- Locate sdkmanager on hosted runner
- Package FCEUmm Android libretro output
- Align Android Java and Kotlin JVM targets
- Harden NES ROM lifetime and video pixel formats
- Use NES core reported AV timing
- Use NES core reported AV timing
- Use NES core reported AV timing
- Use NES core reported AV timing
- Add NES PCM audio output
- Add NES player reset and save-state controls
- Fix FCEUmm ROM loading with content filename
- Provide FCEUmm extended game content info
- Add NES touchscreen controls
- Stabilize development APK signing and versioning
- Make NES player immersive and keep touch controls reachable
- Reassert immersive mode for Samsung foldables
- Add in-app development updater
- Publish development builds to update channel

Evidence: https://github.com/mercurym4/Command-Center-Updates/blob/effe80bb3662d7b66e81fe1b167130d8ead535da/latest.json

