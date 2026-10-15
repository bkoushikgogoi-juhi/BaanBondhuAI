# BaanBondhu AI Android APK build

This is an Android WebView wrapper for the provided BaanBondhu AI website.

## Build the APK using GitHub Actions (no Android SDK needed on your PC)
1. Create a GitHub repository and upload all files in this folder.
2. Open the repository's **Actions** tab.
3. Choose **Build BaanBondhu AI APK** and click **Run workflow** (or push to `main`).
4. Open the completed workflow run and download the `BaanBondhuAI-debug-apk` artifact.
5. Extract the downloaded artifact ZIP; inside is `app-debug.apk`.
6. Send `app-debug.apk` to your guide teacher.

## Important testing notes
- This is a debug APK for demonstration/testing, not a Play Store release.
- The map uses Leaflet and online map tiles; those parts need internet and may not work offline.
- Audio file was supplied as AAC, so the app uses the `.aac` filename/type.
- Test on an Android phone before showing it to your teacher. This build has not been compiled or tested on a physical Android device in this environment.
