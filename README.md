# EnglishUp-NewLevel — Android project

## Included
- Native Android app using Kotlin + Jetpack Compose
- Dark UI and six navigation areas
- A1 lesson and multiple-choice quiz
- Listening practice with Android Text-to-Speech (en-US)
- Speaking practice with Android SpeechRecognizer (en-US)
- Vocabulary cards with pronunciation
- XP and daily mission progress persisted locally with SharedPreferences
- Share your written answer to ChatGPT or another AI app for correction

## Build
1. Install Android Studio (Hedgehog or newer) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync and download dependencies.
4. Connect your Android phone with USB debugging enabled, or create an emulator.
5. Press Run.

To generate an APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

## Important limitations
- This is a functional starter app, not a hosted cloud service.
- AI correction is handed off through Android's share menu; no private API key is embedded.
- Speech recognition depends on Android's installed speech recognition service and may use Google's online service.
- Progress is stored locally on this device; no account sync or cloud backup has been implemented.
- This source project has not been compiled in this environment. Android Studio/Gradle should be used to validate and build it.
