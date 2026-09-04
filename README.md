# GG Browser — GitHub-ready Android project

This repository is prepared for a phone-only GitHub Actions build.

## Build the APK from your phone

1. Create a GitHub repository.
2. Upload the **contents of this folder** to the repository (including `.github`).
3. Open the repository's **Actions** tab.
4. Select **Build GG Browser**.
5. Tap **Run workflow**.
6. Wait for the workflow to finish.
7. Open the completed workflow run.
8. Under **Artifacts**, download **GG-Browser-APK**.
9. Extract the downloaded artifact and install `app-debug.apk`.

The workflow uses GitHub's hosted Linux runner, Java 17, Android SDK 35, and Gradle 8.10.

## Current build

This is the first core browser build. It includes:
- Web browsing
- Address/search bar
- Back, forward, reload
- Google search
- Downloads
- Find in page
- Desktop user-agent toggle
- Basic private mode
- JavaScript and DOM storage
- Cookie controls
- Camera/microphone permission support
- Dark-mode capability where supported by Android System WebView

More advanced browser features (full tab management, persistent bookmarks/history UI, richer privacy controls, etc.) can be added in later versions.
