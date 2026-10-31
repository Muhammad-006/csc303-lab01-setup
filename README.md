# CSC303 Lab 01 - Android Studio setup, build, run and debugging

Project: **Lab01Setup** (Kotlin, Jetpack Compose, Material 3)
Package: `com.example.lab01setup`
Student: Muhammad Bilal - FA23-BCE-062

## What this project shows
- A starter Compose app, personalised to display the course, lab number, name and registration number.
- A tagged diagnostic message in `MainActivity.onCreate()` (`Log.d("CSC303-Lab01", ...)`) used for the Logcat / debugger task.

## Build configuration
| Item | Value |
|------|-------|
| Android Gradle Plugin | 9.4.0 |
| Gradle (wrapper) | 9.6.0 |
| Kotlin | 2.4.21 |
| Compose BOM | 2026.09.00 |
| compileSdk / targetSdk / minSdk | 36 / 36 / 26 |

## Run
1. Open this folder in Android Studio (File > Open) and wait for Gradle sync.
2. Start an emulator (Device Manager) or connect a phone with USB debugging.
3. Run the `app` configuration, or from the terminal: `.\gradlew.bat installDebug`.

## Logcat check
Filter with `tag:CSC303-Lab01` - the message `MainActivity onCreate called` must appear.

## Evidence (fill in after running)
| Item | Value |
|------|-------|
| Android Studio version | |
| Device / API level | |
| First build result | |
| Git commit ID (`git log --oneline -1`) | |
