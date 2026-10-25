# Habit Tracker (Android)

WebView app. The whole UI is in `app/src/main/assets/index.html`.

## Build the APK on GitHub
1. Upload everything in this folder to the root of a GitHub repo (the `.github` folder must come with it).
2. Open the **Actions** tab, pick **Build APK**, press **Run workflow** (it also runs on every push).
3. When the run is green, open it and download **HabitTracker-APK** from *Artifacts*, unzip it, and install `app-debug.apk`.

If the Actions tab does not show "Build APK", create the file `.github/workflows/build.yml` in GitHub
(Add file > Create new file) and paste the contents of `build-workflow-copy.yml`.
