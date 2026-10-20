# Snakes & Ladders PWA — phone-friendly setup

This is a starter Progressive Web App (PWA) package of your existing game. It includes the game,
web app manifest, icons, and a basic offline service worker. It is not an Android APK/AAB and is
not yet published online.

## Upload using only your Android phone
1. Sign in to GitHub in your mobile browser and create a new repository. For a beginner, a public
   repository is easiest for GitHub Pages; do not put passwords or private information in it.
2. Upload the contents of this folder to the repository root. Make sure `index.html`,
   `manifest.webmanifest`, and `sw.js` are at the root, and the `icons` folder is also uploaded.
3. In the repository, open Settings → Pages. Choose deployment from the main branch and the root
   folder, then save. Wait for GitHub Pages to provide the published URL.
4. Open the HTTPS URL in Chrome on Android. Test the whole game online first, then reload and
   test offline. The service worker only works on HTTPS or localhost.
5. Open PWABuilder and enter the published URL. Run its checks. If the checks pass, explore its
   Android package workflow and follow its current signing and asset instructions.
6. A packaged Android app still needs to meet Google Play's current technical, policy, privacy,
   and testing requirements. Check the generated package before uploading.

## Important
- This is a starter PWA, not a ready-to-upload signed Android App Bundle.
- Do not claim the app collects no data until you verify the final package and any added SDKs.
- Current Google Play requirement for new apps/updates (from 31 August 2026) is target API 36 or
  higher. Confirm current requirements in Play Console and the official policy page.
- If your developer account is subject to the new personal-account testing rules, complete the
  required closed test before applying for production access.
- Keep the game code and any signing credentials backed up. Never share signing key passwords.
