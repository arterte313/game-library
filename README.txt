GAME LIBRARY — Android setup

Included: Played and To Play lists, add/edit/delete, custom title/description/image, local saving, offline support.

EASIEST TEST:
1. Extract this ZIP.
2. Open index.html in your phone browser. (If your browser opens it as a file, you can use the app and data should persist in that browser, but installation/offline PWA features require hosting over HTTPS.)
3. To use it as an installable app, host these files on a free HTTPS static host such as GitHub Pages:
   - Create a GitHub account/site repository.
   - Upload index.html, manifest.json, sw.js and icon.svg to the repository root.
   - In repository Settings → Pages, choose deploy from branch (main / root) and save.
   - Open the generated HTTPS Pages URL in Chrome on Android.
   - Chrome menu ⋮ → “Install app” or “Add to Home screen”.
4. Launch it from the new home-screen icon. Entries are saved automatically on this phone/browser, even after closing it.

IMPORTANT:
- The lists are stored on the device in the browser's local storage. Clearing browser/site data or uninstalling/clearing the installed app's storage can erase your library.
- Use image files you have access to. Cover images are resized/compressed before saving.
- This is a lightweight web app packaged for installation as a PWA; it is not an APK.
