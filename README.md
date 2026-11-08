# ChatGPT VIP PRO – Android starter project

This is an Android Studio project starter with both:
- a built-in VIP PRO prompt mode
- an AI chat panel configured to call your own backend endpoint

## Build APK
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Android Studio will show the generated APK path.

## AI connection
The app's AI tab sends POST JSON `{ "question": "...", "mode": "step_by_step" }` to the backend URL entered in the app. Backend should return JSON with `answer` (or `output`).
Do not place a private API key in the Android app. Use a backend service to keep secrets safe.

This starter source is not an already-compiled APK. Build it in Android Studio.
