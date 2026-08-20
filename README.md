# TextVault

TextVault is a simple, privacy-focused plain-text notes Android app. Notes are saved as real .txt files in a user-selected folder using the Storage Access Framework.

This repository includes a GitHub Actions workflow that builds a debug APK and uploads it as an artifact.

Features:
- Create / edit / delete plain text notes (.txt files)
- Choose storage folder with SAF (persisted URI permission)
- Optional PIN lock using EncryptedSharedPreferences

Build:
- The workflow at .github/workflows/build-apk.yml builds the debug APK on push to main.

Trigger: build started by Copilot on 2026-08-20 to run the CI build.
