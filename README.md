# Quickgram

A starter social-media-style Android app built with HTML/CSS/JavaScript and Capacitor.

## Important
- This is a front-end demo. Login is local demo validation, not secure authentication.
- Posts are in memory and reset when the app restarts.
- Do not use real passwords or publish private user content.
- For real multi-user accounts, posts, uploads, and moderation, connect Firebase or another secure backend.

## Build APK using only an Android phone
1. Create a GitHub repository named `Quickgram`.
2. Upload all files and folders from this project to the repository (keep `.github/workflows/build-apk.yml`).
3. Open the repository on GitHub in Chrome. Enable Desktop site if needed.
4. Open **Actions** and enable workflows if GitHub asks.
5. Select **Build Quickgram Android APK** and press **Run workflow**.
6. Wait for the workflow to finish successfully.
7. Open the completed run and download **Quickgram-debug-apk** under Artifacts.
8. Extract the ZIP on your phone, tap `app-debug.apk`, and follow Android's install prompt.

## Publish a release
After the workflow succeeds, create a GitHub Release and attach the downloaded APK. A debug APK is suitable for testing; for wider distribution, create a signed release APK/AAB and protect the signing key.

## Edit the app
Edit `index.html`, commit changes to `main`, then run the workflow again.
