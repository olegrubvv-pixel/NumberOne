# Number Games — Android APK project

This is a native Android Studio project that packages the Number Games web UI inside an Android WebView.

## Build an APK

1. Install Android Studio.
2. Open this folder: `NumberGames_APK_Project`.
3. Let Android Studio sync/download the Gradle and Android dependencies.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be under:
   `app/build/outputs/apk/debug/app-debug.apk`

For a release APK:
- Use **Build > Generate Signed App Bundle / APK**.
- Create or select a signing key.
- Choose APK and build the release variant.

## App details

Package: `com.numbergames.app`
Name: `Number Games`
Version: `1.0`

The app works offline after installation because the HTML/CSS/JavaScript is bundled into the APK.
