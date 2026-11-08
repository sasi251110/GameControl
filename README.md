# GameControl

Virtual PlayStation-style game controller for Android (Phase 1: controller UI).

## Build

- Android Studio: open this folder, then Sync Gradle and press Run.
- Command line: run `gradle wrapper --gradle-version 8.9` once (creates `gradlew`), then `./gradlew assembleDebug`.

The GitHub Actions workflow creates the Gradle wrapper automatically if it is missing.

Requires JDK 17. Minimum Android version: 8.0 (API 26).
