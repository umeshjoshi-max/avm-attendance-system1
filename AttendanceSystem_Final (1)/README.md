
AVM Attendance System - Ready Android Project (Final)

How to use:
1. Unzip and open the folder in Android Studio OR push to GitHub.
2. If pushing to GitHub, the included workflow will install Gradle on the runner and build an unsigned release APK.
3. After push, go to Actions -> select build run -> download artifact named 'avm-release-apk'.

Notes:
- This project builds an unsigned release APK by default. To create a signed APK, add your keystore and signingConfig in app/build.gradle.
