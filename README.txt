StatusLock - double tap the status bar to lock the screen.

Build:
1. Open this folder in Android Studio (File > Open). Let Gradle sync.
2. Build > Build APK(s), or press Run with your phone connected.
   (Release builds are signed with the debug key so they install directly.)

Setup on phone:
1. Open the app; it jumps to Accessibility settings.
2. Installed apps > StatusLock > turn on.
3. If greyed out: Settings > Apps > StatusLock > menu > Allow restricted settings.
4. Set the app's battery usage to Unrestricted so Samsung doesn't kill it.

No Android Studio? Build online with GitHub Actions:
1. Create a free GitHub repo and upload everything in this folder
   (including the hidden .github folder).
2. Open the Actions tab > "Build APK" > wait ~3 min.
3. Download the StatusLock-apk artifact, unzip, install the .apk.
