درس منزلة الصلاة - Android project
===================================
Option A (no installs, easiest): GitHub
  1. Create a free GitHub repository and upload ALL files of this folder
     (keep the .github folder).
  2. Open the "Actions" tab -> "Build APK" runs automatically (or press "Run workflow").
  3. When it finishes, open the run and download the "salah-lesson-apk" artifact.
     Unzip it -> salah-lesson.apk -> install on the phone.

Option B: Android Studio
  File > Open > pick this folder > wait for sync >
  Build > Build APK(s)  (or Build > Generate Signed Bundle / APK).
  Output: app/build/outputs/apk/release/app-release.apk

The lesson page itself is app/src/main/assets/index.html
