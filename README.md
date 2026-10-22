# Benimation releases

Signed Android and Windows downloads for Benimation. Application source remains private.

## Current release: 0.8.2

[Android APK](https://github.com/Benighter/Benimation-Releases/releases/download/v0.8.2/Benimation-0.8.2.apk) · [Windows portable ZIP](https://github.com/Benighter/Benimation-Releases/releases/download/v0.8.2/Benimation-0.8.2-Windows-x64.zip) · [Release notes and checksums](https://github.com/Benighter/Benimation-Releases/releases/tag/v0.8.2)

The season picker finds related Baki series across both catalogues, and Home and search suggestions keep AnimeSaga titles visible. Searches remain pending until the other catalogue finishes.

Aniwatch and AnimeSaga share search, browsing, matching titles, episodes and the player. Available titles and episodes now appear while other providers finish loading. Video can start without waiting for every alternative server. Late results preserve the current episode, audio choice, source and watching position. Favorites, watched episodes, concurrent downloads and Continue Watching remain available.

Android retains package `com.benighter.benimation`, the existing signing identity and in-app update feed. The app checks on launch and while open, verifies the APK and asks for Android's installation approval. Windows includes the signed executable and WebView2 loader; extract all ZIP contents together. Its signing certificate is self-signed.

Verification includes timed native Windows loading, Android-emulator playback and source switching, blocked-provider regressions, rendered source selection and Android release lint. Media buffering still depends on the video host and connection. Physical-phone testing is not claimed.

[App library](https://benighters-personal-projects.vercel.app/) · [Android update manifest](https://github.com/Benighter/Benimation-Releases/releases/latest/download/android-update.json) · [Windows download manifest](https://github.com/Benighter/Benimation-Releases/releases/latest/download/windows-update.json)
