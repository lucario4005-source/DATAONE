GOOGLE HUB - Android app project

What it does:
- Shows four simple buttons: Gmail, Google Photos, Google Drive, Google Account.
- Each button opens the official Google service in your phone's browser or installed app.
- It does not store or copy your Google data.

To get an APK using GitHub (free for a small public repository):
1. Create a new repository on https://github.com and name it GoogleHub.
2. Upload all files and folders in this project to the repository root. Make sure .github/workflows/build-apk.yml is included.
3. Open the repository's Actions tab. Select "Build Google Hub APK" and tap "Run workflow" (or wait for the first push build to finish).
4. Open the completed workflow run and download the "Google-Hub-APK" artifact. It downloads as a ZIP; extract it to find app-debug.apk.
5. Open app-debug.apk on your Android phone and allow installation from that source if Android asks.

To edit the app later, edit app/src/main/java/com/viral/googlehub/MainActivity.java. The service labels and links are in addService(...) calls. Push the change to GitHub and run the workflow again.
