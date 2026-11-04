J.A.R.V.I.S. Habit Tracker — Android APK project

This is a native Android WebView wrapper around the existing offline-first habit tracker.
The Android APK must be compiled using Android SDK/Gradle. This runtime does not have an Android SDK or Gradle installed, so it cannot produce the APK binary directly.

BUILD IN GITHUB (no local Android SDK required)
1. Sign in to GitHub and create a new repository.
2. Upload the CONTENTS of this folder to the repository (keep .github/workflows/build-apk.yml).
3. Open the repository's Actions tab.
4. Select "Build JARVIS APK" and run the workflow (or push to main).
5. When it finishes, open the workflow run and download the artifact named "JARVIS-Habit-Tracker-APK".
6. Extract the artifact. Install app-debug.apk on your Android phone. If Android asks, allow installation from that source.

For a personal debug APK, this is sufficient. A Play Store release needs a separately generated signing key and a signed release build.

App data is stored locally in WebView storage. Keep using Settings > Export backup to protect records.
