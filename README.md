# The Path — Version 4

A phone-first, installable dark-fantasy life-RPG prototype with themed regions and story fragments.

## Files
- `index.html` — the app
- `manifest.json` — installable web app settings
- `sw.js` — offline shell cache
- `icon.svg` — app icon

## Publish with GitHub Pages
1. Create a new **public** GitHub repository (GitHub Free Pages requires a public repository).
2. Upload all five files directly into the repository root. Do not put them inside another folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/(root)`, then Save.
6. Wait for the published URL to appear.

The repository and published website are public. Do not put private or sensitive information in the repository.

## Add to iPhone
1. Open the published URL in Safari.
2. Tap Share → Add to Home Screen.
3. If shown, enable **Open as Web App**, then tap Add.

## Version 4 design changes
- The welcome hero, greeting, stats, and XP bar now appear only on the Home / Sanctuary tab.
- Removed repeated headings inside several sections to make the interface calmer and easier to scan.
- Added distinct real-world photographs and a photograph of a historical illuminated manuscript to section banners, the map, and character portrait.
- Updated the service-worker cache name so installed copies can refresh the new app shell.

## Version 3 design changes
- Reworked the interface for phone-first use, including a compact fixed bottom navigation bar with all seven sections.
- Each section has its own palette, sigil, introductory banner, and atmosphere.
- World exploration now reveals persistent lore fragments as regions are visited.
- The Forge becomes available at level 5.
- Existing V2 progress is retained because the app continues using the same local storage key.

## Current features
- Sanctuary dashboard
- Six attributes: Vigor, Mind, Discipline, Wisdom, Order, Spirit
- XP, levels, quest completion, attribute progression
- Custom quests and difficulty rewards
- Clickable world map regions with collectible lore fragments; the Northern Forge opens at level 5
- Distinct visual identity for each tab: Sanctuary, World, Quests, Character, Chronicle, Reliquary, and Stillroom
- Larger mobile touch targets, safe-area-aware navigation, improved form sizing, and a seven-tab bottom bar
- iPhone-style standalone web app metadata
- Clickable world map regions
- Character name, calling, and emblem
- 66-day campaign counter
- Journal and mood check-in
- Collectibles / achievements
- Focus timer and daily intention
- Local browser storage
- Offline shell caching

## Important notification limitation
This prototype can request browser notification permission and schedule a reminder **while the app remains open**. It does **not** yet deliver reliable scheduled notifications while the app is closed. True background push requires a push provider or a server that sends Web Push messages, plus subscription storage and VAPID/server configuration. Do not assume the notification toggle provides background push.

## Artwork and licensing
The app uses real photographs and a photograph of a historical manuscript; it does not use AI-generated artwork. Existing Unsplash photographs are credited here:
- Gianluca Giarda — [Ancient castle ruins on a misty, forested hilltop](https://unsplash.com/photos/ancient-castle-ruins-on-a-misty-forested-hilltop-46KN_z1ubuQ)
- Valentin Zickner — [Ancient stone tower ruins amidst dense green forest](https://unsplash.com/photos/ancient-stone-tower-ruins-amidst-dense-green-forest-5BvIyxlG5_o)

The app uses those externally hosted photographs; it does not generate artwork. They require an internet connection. Confirm current license terms and attribution requirements before redistributing or modifying images. Fonts are loaded from Google Fonts and also require internet access.

## Data and privacy
Progress is stored in localStorage in the current browser/device. It is not synced between devices and can be lost if browser site data is cleared. Do not store sensitive personal information.


Additional artwork used in Version 4 (Wikimedia Commons):
- Abdul Rahman Abdul Kudus, “A view of a forest path” — CC BY-SA 4.0: https://commons.wikimedia.org/wiki/File:A_view_of_a_forest_path.jpg
- Jo Dowdall, “Medieval castle ruins clonmacnoise” — CC BY-SA 4.0: https://commons.wikimedia.org/wiki/File:Medieval_castle_ruins_clonmacnoise.jpg
- JeroenVEB, “Illuminated manuscript” (photograph of a historic manuscript leaf) — CC0: https://commons.wikimedia.org/wiki/File:Illuminated_manuscript.jpg
- NotFromUtrecht, “Tintern Abbey interior” — CC BY-SA 3.0: https://commons.wikimedia.org/wiki/File:Tintern_Abbey_interior.JPG

Images are externally hosted and require an internet connection. The Commons files retain their stated licenses; see each source page for full terms and attribution details.
