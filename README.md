# 📺 Nahiyan IPTV

[![Android](https://img.shields.io/badge/OS-Android%20%7C%20Google%20TV-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](#)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=for-the-badge&logo=android&logoColor=white)](#)
[![Media3](https://img.shields.io/badge/Engine-ExoPlayer%20Media3-000000?style=for-the-badge)](#)

A masterclass in Android streaming. **Nahiyan IPTV** is a premium, ad-free IPTV client built entirely from scratch using modern Jetpack Compose and ExoPlayer architectures. Engineered specifically to handle massive playlists, prevent stream freezing, and deliver a native, lightning-fast experience on both Android Mobile and Android TV.

🌐 **[Official Download Page](https://[your-username].github.io/nahiyan-iptv-app/)** *(Replace with your actual GitHub Pages URL)*

---

## ✨ Core Features

**⚡ Zero-Freeze Watchdog Engine** Cheap hardware decoders and dropped packets ruin live sports. Nahiyan IPTV features a custom timeline-tracking watchdog. If a stream silently drops a frame or freezes for 5 seconds, the app brutally flushes the TV's decoder memory and rebuilds the stream in the background without user intervention.

**🔍 Global Universal Search** Stop digging through menus. The unified search engine queries across Live Channels, VOD Movies, and TV Series simultaneously. Type 2 letters, and instantly jump to your content.

**A Advanced VOD Media Tracks** Total control over your movies. The player automatically parses embedded tracks, allowing you to hot-swap between multiple Audio Languages and Subtitle files directly from the playback interface.

**📺 Native TV-First Interface** Built natively for the D-Pad. Features distinct hover states, auto-hiding OSD controls, and leanback compatibility for NVIDIA Shield, Google TV Chromecasts, and Sony/TCL Smart TVs.

**📻 Live EPG & Auto-Resume** Integrated Electronic Program Guide parsing shows 'Now' and 'Next' programming natively inside the player UI. VODs and Series automatically save your timestamp and resume exactly where you left off.

---

## 🔌 Supported Providers & Formats

* **Xtream Codes API:** Full support for Live, VOD, Series, and Categories.
* **M3U / M3U8 Playlists:** Fast parsing for remote URL playlists.
* **Direct Streams:** Play uncompressed `.ts`, `.mp4`, and `.mkv` network streams.
* **Decoders:** Automatic hardware-to-software decoder fallback to ensure compatibility with heavily compressed files.

---

## 📥 Installation

1. Navigate to the **[Official Download Page](https://spectralguise.github.io/nahiyan-iptv-app/)**.
2. Click **Download APK**.
3. Transfer the `.apk` to your Android TV or Android Phone (via USB, Downloader app, or Send Files to TV).
4. Enable **Unknown Sources** in your device settings.
5. Install and launch **Nahiyan IPTV**.

---

## 🛠️ The Tech Stack

This application bypasses legacy XML views and relies on the absolute latest Android development standards:
* **100% Jetpack Compose:** For a fluid, state-driven UI.
* **AndroidX Media3 (ExoPlayer):** Utilizing `DefaultMediaSourceFactory` and customized `DefaultExtractorsFactory` to force-read corrupted `.ts` IPTV packets.
* **Kotlin Coroutines & Flow:** For non-blocking, asynchronous playlist parsing and network calls.
* **Coil3:** For aggressive, low-memory image caching of channel logos and VOD posters.

---

*Disclaimer: Nahiyan IPTV is a media player. It does not provide, host, or contain any media content. Users must provide their own legally acquired playlists or server credentials.*
