# Electoral India Android WebView

This project wraps the hosted Electoral India website in a native Android WebView. The PostgreSQL backend remains on the website's existing server; no database credentials belong in this app.

## Build without Android Studio

1. Push to the `main` or `master` branch, or open **Actions → Build Android APK → Run workflow** on GitHub.
2. Open the completed workflow run and download the `electoral-india-debug-apk` artifact.
3. Extract `app-debug.apk`, transfer it to your Android phone, and install it. The phone may ask you to allow installs from the app you used to open the APK.

The debug APK is for testing and can be rebuilt by anyone with repository access. A publishable release requires a signed release build and a securely stored signing key.
