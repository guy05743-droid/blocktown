BLOCKTOWN ANDROID PROJECT

This is an Android Studio project that wraps the supplied Blocktown HTML game in a full-screen Android WebView.

BUILD THE APK
1. Extract the BlocktownAndroid folder.
2. Open Android Studio and choose Open, then select this folder.
3. Allow Android Studio to sync/download the Android Gradle plugin and SDK components.
4. Connect an Android phone with USB debugging enabled, or use an emulator.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. The debug APK will be in app/build/outputs/apk/debug/app-debug.apk.

NOTES
- Internet is required because the HTML game loads some libraries from CDNs and uses online multiplayer services.
- The project uses a WebView wrapper; it does not rewrite the game in native Android code.
- For release/public distribution, create a signed APK or AAB in Android Studio.
- The app is configured for landscape orientation because the game uses a wide game layout.
