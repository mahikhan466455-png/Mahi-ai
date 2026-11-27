# Mahi AI

A small Hindi-friendly AI chat web app that can be packaged for Android with Capacitor.

## Configure AI
Open the app, tap the gear icon, and enter a Gemini API key. The key is stored locally in the browser/app storage. Do not publish your key or commit it to GitHub.

## Android build
The GitHub Actions workflow in `.github/workflows/build-apk.yml` creates the Android project, builds a debug APK, and uploads it as an artifact.

Note: this starter calls Gemini directly from the client. For a public production app, use a secure backend so API keys are not exposed to users.