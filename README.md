# Stack Up — Android project

This project packages the original `Stack Up v4 - Part 17.html` game in a native Android WebView shell. The original HTML/CSS/JavaScript game is preserved at `app/src/main/assets/index.html`.

## Build an APK with Android Studio

1. Install the latest Android Studio.
2. Open this `StackUp-Android` folder (the folder containing `settings.gradle`).
3. Allow Android Studio to sync and install the Android SDK Platform 35 / required build tools if prompted.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. When the build completes, choose **locate**. The debug APK is normally at `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer the APK to your Android phone and install it. If Android asks, allow installation from that source.

## Notes

- App name: Stack Up
- Application ID: `com.stackup.game`
- Minimum Android version: Android 6.0 (API 23)
- Portrait orientation; immersive full-screen game display.
- JavaScript and local storage are enabled so the game and saved progress can work in the WebView.
- Internet permission is included for the optional Google Fonts referenced by the original HTML. The game itself is bundled locally.

This is an Android Studio project, not a precompiled APK. A compatible Android SDK/Gradle build environment is required to compile the installable APK.
