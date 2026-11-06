# FitGoal 64

A personal Android fitness tracker built with Kotlin and Jetpack Compose.

## Included
- Dashboard for the 81 kg starting weight and 64 kg target
- Daily calorie, protein, water and weight check-in
- Local progress history and weight trend chart
- Home strength workout schedule
- Indian vegetarian + egg meal guide
- Dark green fitness interface

## Build the APK

### Option A: Android Studio
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Find the APK at `app/build/outputs/apk/debug/app-debug.apk`.

### Option B: GitHub Actions
1. Create a GitHub repository and upload all files in this project.
2. Push to the `main` branch, or open **Actions → Build Android APK → Run workflow**.
3. When the workflow finishes, download the `FitGoal64-debug-apk` artifact.

## Upload to GitHub
Create a repository named `FitGoal64`, then upload the contents of this folder (not the ZIP file itself, unless you prefer to keep the ZIP as a release asset).

## Personalization and privacy
- The app stores check-ins locally on the Android device using SharedPreferences.
- It does not require an account or send health/fitness data to a server.
- Uninstalling the app or clearing its storage may erase locally saved entries.
- The calorie and protein targets are editable guidance, not medical advice. Adjust them based on your progress, activity and professional guidance where appropriate.

## Notes
This project is provided as source code. An APK is not bundled; build it with Android Studio or GitHub Actions.
