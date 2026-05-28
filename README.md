# Stardew Perfection Tracker PWA

This is your Stardew Valley perfection tracker as a small installable web app.

## Files

- `index.html` - the tracker
- `manifest.json` - tells Android/Chrome this is an installable app
- `service-worker.js` - makes it work offline after first load
- `icons/` - app icons

## Best way to use it on Android

1. Upload this folder to GitHub Pages, Netlify, or another static web host.
2. Open the hosted link in Android Chrome.
3. Tap the three-dot menu.
4. Tap **Add to Home screen** or **Install app**.
5. Open it from your home screen.

Your tick boxes will save automatically on that phone/browser.

## Backup

Use **Export Progress JSON** inside the tracker from time to time.
Use **Import Progress JSON** to restore or move progress to another device.

## GitHub Pages quick setup

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Go to repository **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait a minute, then open the GitHub Pages link shown on that page.
