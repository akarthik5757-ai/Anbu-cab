ANBU TOUR & TRAVELS — Android app project
=========================================

WHAT THIS PROJECT DOES
- Opens https://anbucab.netlify.app/ inside an Android app.
- Supports website JavaScript and local browser storage.
- Allows file inputs on the website to open the phone's photo/file picker.
- Opens tel: links in the phone dialler and WhatsApp links in supported apps.
- External HTTPS links open in the browser.

IMPORTANT LIMITATION
This APK wrapper does not automatically create missing website features.
The website itself must implement:
1. WhatsApp booking links/forms,
2. owner photo upload and cloud storage,
3. customer reviews and owner approval with a secure owner login,
4. Tamil/English language switching,
5. click-to-call links.
Owner uploads and review approval need a backend/database/storage service to sync publicly.

BUILD THE APK USING YOUR ANDROID PHONE
1. Download and extract this ZIP.
2. Create/sign in to GitHub and create a new repository, e.g. AnbuTourTravelsAndroid.
3. Upload the extracted project files/folders to the repository root (not the ZIP itself).
4. Open the repository's Actions tab.
5. Select "Build Android APK" and press "Run workflow". If prompted, enable Actions.
6. When the workflow finishes successfully, open the run and download the artifact named
   "anbu-tour-travels-debug-apk".
7. Extract the downloaded artifact ZIP to get app-debug.apk.
8. Open the APK on your Android phone. If Android asks, allow installation from that source.
   Only install APKs you built or trust.

NOTE
This is a DEBUG APK for testing, not a Play Store release. A release APK should be signed.
The workflow uses Gradle installed on the GitHub runner, so a Gradle wrapper is not required.
