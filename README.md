# Benimation releases

Signed Android and Windows downloads for Benimation. Application source remains private.

## Current release: 0.8.0

[Android APK](https://github.com/Benighter/Benimation-Releases/releases/download/v0.8.0/Benimation-0.8.0.apk) · [Windows portable ZIP](https://github.com/Benighter/Benimation-Releases/releases/download/v0.8.0/Benimation-0.8.0-Windows-x64.zip) · [Release notes and checksums](https://github.com/Benighter/Benimation-Releases/releases/tag/v0.8.0)

Aniwatch and AnimeSaga now share search, browsing, episodes and the player. Matching titles combine available sources, and switching sources keeps your watching position. Favorites, watched episodes and Continue Watching stay together; if one source is unavailable, the other catalogue remains usable. Different seasons remain separate. Persistent watched checkboxes and concurrent individual and whole-season downloads remain available.

Android retains package `com.benighter.benimation`, the existing signing identity and verified in-app update feed. The app checks on launch and while open, shows release notes and verifies the APK before Android asks you to confirm installation. Windows includes the signed executable and WebView2 loader; extract all ZIP contents together. The Windows certificate is self-signed.

Verification includes real playback from both providers on Windows and the Android emulator, source switching with resume, provider tests, Android release lint and shared interface checks. Physical-phone testing is not claimed. Catalogue and media availability depend on external providers.

[App library](https://benighters-personal-projects.vercel.app/) · [Android update manifest](https://github.com/Benighter/Benimation-Releases/releases/latest/download/android-update.json) · [Windows download manifest](https://github.com/Benighter/Benimation-Releases/releases/latest/download/windows-update.json)
