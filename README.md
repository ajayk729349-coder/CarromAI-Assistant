# Carrom AI Assistant (Android Project)

Complete, build-ready Android project with Android 14/15 `MediaProjection.Callback` fixes, runtime `POST_NOTIFICATIONS` permission handling, `app/build.gradle`, and a GitHub Actions workflow to build an installable APK in the cloud without needing Android Studio locally.

## Option 1: Build APK via GitHub Actions (No Local Android Studio Needed)
1. Create a new repository on GitHub (e.g., `CarromAI-Assistant`) and upload the contents of this folder.
2. Open the **Actions** tab in your GitHub repository.
3. Run **Build Android Debug APK** (or push to `main`).
4. Once finished, download **CarromAI-Assistant-debug** from the **Artifacts** section and extract `app-debug.apk` onto your Android phone.

## Option 2: Build APK in Android Studio
1. Open this extracted folder in Android Studio (Ladybug or newer) with Android SDK 35 installed.
2. Wait for Gradle sync to finish.
3. Go to **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Locate `app/build/outputs/apk/debug/app-debug.apk` and install it on your device.
