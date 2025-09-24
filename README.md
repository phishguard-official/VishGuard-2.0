CallGuard Android (minimal)
===========================
This is a minimal native Android (Kotlin) project that listens to microphone input
and warns when scam-like phrases are detected. It uses Android SpeechRecognizer and TextToSpeech.

How to build:
- Open this project in Android Studio (File -> Open) and let it sync.
- Connect your phone (or use Codemagic) and run Build -> Build Bundle(s) / APK(s) -> Build APK(s).

Notes:
- For CI (Codemagic), upload the repository (include entire folder) and run an Android build workflow.
- This project intentionally avoids third-party plugins to make building simpler.
