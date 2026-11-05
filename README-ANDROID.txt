SMART HOME AI PRO — Android APK build package

This package contains the premium web app and a GitHub Actions workflow that builds a DEBUG APK.
It does not contain a prebuilt APK. GitHub Actions builds the APK after you upload/commit these files.

HOW TO USE
1. Download and extract this ZIP.
2. In your GitHub repository horbitamir6-lab/smart-home-ai-pro, upload the CONTENTS of this folder (including the hidden .github folder) to the repository root, replacing the old index.html if prompted.
3. Commit the changes to the main branch.
4. Open the repository on GitHub > Actions.
5. Open the workflow "Build SMART HOME AI PRO APK". Wait until it finishes with a green check.
6. Open the completed workflow run, scroll to Artifacts, and download SMART-HOME-AI-PRO-debug-APK.
7. Extract the downloaded artifact ZIP and tap app-debug.apk on your Android phone to install.
8. Android may ask permission to install unknown apps for the browser/file manager you used. Only allow it for this file if you trust the source.

NOTES
- This is a DEBUG APK for testing, not a Play Store release.
- The app keeps its data locally on the device/browser storage.
- The assistant in this MVP is a local demo assistant, not a connected cloud AI service.
- For a Play Store release, a separately signed release build and privacy/security review are needed.
