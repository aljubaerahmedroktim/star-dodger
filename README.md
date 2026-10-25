# Star Dodger – build the APK
Option A (no installs): push this folder to a new GitHub repo. Actions > "Build APK" > download the `star-dodger-apk` artifact (app-debug.apk).
Option B (local, needs Node 20, JDK 17, Android SDK): npm install && npx cap add android && npx cap sync android && cd android && ./gradlew assembleDebug
The APK appears at android/app/build/outputs/apk/debug/app-debug.apk. Enable "install unknown apps" on your phone to sideload it.
