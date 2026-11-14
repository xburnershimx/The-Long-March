# The Path — Version 2

A responsive, installable dark-fantasy life-RPG prototype.

## Files
- `index.html` — the app
- `manifest.json` — installable web app settings
- `sw.js` — offline shell cache
- `icon.svg` — app icon

## Publish with GitHub Pages
1. Create a new **public** GitHub repository (GitHub Free Pages requires a public repository).
2. Upload all four files directly into the repository root. Do not put them inside another folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/(root)`, then Save.
6. Wait for the published URL to appear.

The repository and published website are public. Do not put private or sensitive information in the repository.

## Add to iPhone
1. Open the published URL in Safari.
2. Tap Share → Add to Home Screen.
3. If shown, enable **Open as Web App**, then tap Add.

## Current features
- Sanctuary dashboard
- Six attributes: Vigor, Mind, Discipline, Wisdom, Order, Spirit
- XP, levels, quest completion, attribute progression
- Custom quests and difficulty rewards
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
The two environmental photographs are loaded from Unsplash and credited in the app:
- Gianluca Giarda — [Ancient castle ruins on a misty, forested hilltop](https://unsplash.com/photos/ancient-castle-ruins-on-a-misty-forested-hilltop-46KN_z1ubuQ)
- Valentin Zickner — [Ancient stone tower ruins amidst dense green forest](https://unsplash.com/photos/ancient-stone-tower-ruins-amidst-dense-green-forest-5BvIyxlG5_o)

The app uses those externally hosted photographs; it does not generate artwork. They require an internet connection. Confirm current license terms and attribution requirements before redistributing or modifying images. Fonts are loaded from Google Fonts and also require internet access.

## Data and privacy
Progress is stored in localStorage in the current browser/device. It is not synced between devices and can be lost if browser site data is cleared. Do not store sensitive personal information.
