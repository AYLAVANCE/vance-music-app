<p align="center">
  <img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/logo.png" width="140" height="140" alt="Vance Music Logo">
</p>

<h1 align="center">Vance Music</h1>

<p align="center">
  <b>Unlock the full potential of music: Stream effortlessly with one app!</b>
</p>

<p align="center">
  <a href="#download"><img src="https://img.shields.io/badge/Release-v1.0.0-1DB954?style=for-the-badge&logo=github&logoColor=white" alt="Latest Release"></a>
  <a href="#license"><img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge" alt="License: GPL-3.0"></a>
  <a href="https://android.com"><img src="https://img.shields.io/badge/Platform-Android_8.0+-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Platform: Android"></a>
  <a href="https://kotlinlang.org"><img src="https://img.shields.io/badge/Kotlin-2.0-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Language: Kotlin"></a>
  <a href="https://developer.android.com/jetpack/compose"><img src="https://img.shields.io/badge/UI-Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"></a>
</p>

<p align="center">
  <a href="#download">Download</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#features">Features</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#building-from-source">Building</a> •
  <a href="#faq">FAQ</a> •
  <a href="#license">License</a>
</p>

---

**Vance Music** is a modern, high-performance, and privacy-first music player and streaming application for Android. Built from the ground up using **Kotlin**, **Jetpack Compose**, and **Material Design 3**, Vance Music delivers an ad-free, fluid music listening experience with native Subsonic / Navidrome server connectivity, offline downloads, real-time synchronized lyrics, audio equalization, and hardware-backed credential encryption.

---

## 📥 Download

Get the latest release of Vance Music for Android (Android 8.0+ / API 26+).

<p align="center">
  <a href="https://github.com/vance-music/vance-music/releases/latest">
    <img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/github-badge.png" alt="Download from GitHub" height="60">
  </a>
  &nbsp;&nbsp;
  <a href="https://f-droid.org">
    <img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="60">
  </a>
  &nbsp;&nbsp;
  <a href="https://apt.izzysoft.de/fdroid">
    <img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" alt="Get it on IzzyOnDroid" height="60">
  </a>
</p>

### Direct APK Downloads

| Variant | Target Architecture | Minimum Android | Size | Download |
|:---|:---|:---|:---|:---:|
| **Universal** | All Devices (`arm64`, `armeabi-v7a`, `x86_64`) | Android 8.0 (API 26) | ~28 MB | [Download APK](https://github.com/vance-music/vance-music/releases/latest) |
| **ARM64** | Modern Phones & Tablets (`arm64-v8a`) | Android 8.0 (API 26) | ~19 MB | [Download APK](https://github.com/vance-music/vance-music/releases/latest) |
| **ARMv7** | Older 32-bit Devices (`armeabi-v7a`) | Android 8.0 (API 26) | ~18 MB | [Download APK](https://github.com/vance-music/vance-music/releases/latest) |

---

## 📱 Screenshots

<p align="center">
  <table>
    <tr>
      <td align="center"><b>Home Feed</b></td>
      <td align="center"><b>Now Playing</b></td>
      <td align="center"><b>Synchronized Lyrics</b></td>
      <td align="center"><b>Search & Explore</b></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_1.png" width="200" alt="Home Feed"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_2.png" width="200" alt="Now Playing"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_3.png" width="200" alt="Synchronized Lyrics"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_4.png" width="200" alt="Search & Explore"/></td>
    </tr>
    <tr>
      <td align="center"><b>Offline Library</b></td>
      <td align="center"><b>Audio Equalizer</b></td>
      <td align="center"><b>Theme & Appearance</b></td>
      <td align="center"><b>Language Preferences</b></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_5.png" width="200" alt="Offline Library"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_6.png" width="200" alt="Audio Equalizer"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_7.png" width="200" alt="Theme & Appearance"/></td>
      <td><img src="https://raw.githubusercontent.com/gokadzev/Musify/master/assets/screenshots/screenshot_8.png" width="200" alt="Language Preferences"/></td>
    </tr>
  </table>
</p>

---

## ✨ Features

- 🔍 **Online Song Search with Real-Time Suggestions**: Fast, intuitive search with instant auto-suggestions across songs, artists, albums, and playlists.
- 📥 **Offline Listening & Downloads**: Download tracks, full albums, and playlists directly to device storage in original audio quality (FLAC, MP3, AAC) with full offline playback.
- 📜 **Synchronized & Plain Lyrics**: Karaoke-style live-scrolling lyrics synchronized to playback timestamp, alongside static plain lyric support.
- 📻 **Artist Radio & Dynamic Mixes**: Personalized radio stations, daily mixes, and deep cuts automatically curated based on your listening habits.
- 🎚️ **Built-in Equalizer & Presets**: Custom multi-band equalizer with Bass Boost, Virtualizer, and tuned presets (Rock, Pop, Jazz, Electronic, Acoustic, Flat).
- 🎨 **Material You UI & Dynamic Theming**: Sleek Material Design 3 interface with artwork-based dynamic color palette extraction, OLED true-black dark theme, and fluid Compose animations.
- 🚫 **Ad-Free & Privacy-Focused**: Zero advertisements, zero third-party trackers, no behavioral telemetry, and no unsolicited paid subscriptions.
- 🌐 **Personalized Language Curation**: Multi-language onboarding and discovery support (English, Hindi, Punjabi, Tamil, Telugu, Spanish, and more) with automated cloud profile synchronization.
- 🔒 **Hardware-Backed AES-256 GCM Security**: Authentication tokens, OAuth sessions, and server credentials encrypted via the hardware **Android Keystore**.
- ⚡ **Low-RAM Device Optimizations (2GB RAM Ready)**: Tuned ExoPlayer buffer thresholds, Coil memory limits (capped at 15% RAM), and proactive system memory trim listeners.
- 🚗 **Android Auto & Background Playback**: Seamless background playback with lock screen media controls, Bluetooth AVRCP metadata, and Android Auto integration.
- 🔄 **Subsonic & Navidrome Integration**: Full Subsonic API compatibility with automated ngrok warning-page bypass and HTTP Basic Authentication handling.
- 🎧 **Gapless Playback & Crossfade**: Smooth audio transitions between consecutive songs for uninterrupted album and live concert listening.

---

## 🏗️ Architecture & Tech Stack

Vance Music follows modern Android architectural guidelines (**Clean Architecture / MVVM**):

```
┌──────────────────────────────────────────────────────────┐
│                   Jetpack Compose UI                     │
│   (Screens, Navigation Compose, M3 Theming, Components)   │
└────────────────────────────┬─────────────────────────────┘
                             │
┌────────────────────────────▼─────────────────────────────┐
│                       ViewModels                         │
│           (StateFlow, CoroutineScope, UI States)         │
└────────────────────────────┬─────────────────────────────┘
                             │
┌────────────────────────────▼─────────────────────────────┐
│                    Repository Layer                      │
│     (VanceMusicRepository, UserPreferencesRepository)     │
└──────────────┬─────────────────────────────┬─────────────┘
               │                             │
┌──────────────▼──────────────┐┌─────────────▼─────────────┐
│        Remote Sources       ││        Local Sources      │
│  - Retrofit / OkHttp        ││  - Jetpack DataStore      │
│  - Subsonic / Navidrome API ││  - Room Database (Cache)  │
│  - Dedicated Profile API    ││  - Android Keystore (AES) │
│  - ExoPlayer Media3 Engine  ││  - Disk Media Cache       │
└─────────────────────────────┘└───────────────────────────┘
```

### Core Libraries & Technologies

| Layer | Library | Description |
|:---|:---|:---|
| **UI Framework** | [Jetpack Compose](https://developer.android.com/jetpack/compose) | Declarative UI toolkit with Material Design 3 |
| **Media Engine** | [AndroidX Media3 ExoPlayer](https://developer.android.com/media/media3) | Low-latency audio streaming, caching, and background playback |
| **Networking** | [Retrofit 2](https://square.github.io/retrofit/) & [OkHttp 3](https://square.github.io/okhttp/) | REST client with interceptors for Subsonic auth and ngrok bypass |
| **Image Loading** | [Coil 3](https://coil-kt.github.io/coil/) | Fast, memory-efficient image loading for Compose with disk caching |
| **Local Storage** | [Jetpack DataStore](https://developer.android.com/topic/libraries/architecture/datastore) | Asynchronous, reactive key-value persistence |
| **Local Database** | [Room Database](https://developer.android.com/training/data-storage/room) | SQLite abstraction for offline metadata and caching |
| **Security** | [Android Keystore](https://developer.android.com/training/articles/keystore) | Hardware-backed AES-256 GCM encryption for user credentials |
| **Asynchrony** | [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) & Flow | Reactive asynchronous stream processing |

---

## 🛠️ Building From Source

### Prerequisites
- **Android Studio**: Ladybug (2024.2.1+) or newer
- **JDK**: Java Development Kit 17+
- **Android SDK**: Compile SDK 35, Minimum SDK 26
- **Gradle**: 8.7+ (Kotlin DSL)

### Compilation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vance-music/vance-music.git
   cd vance-music
   ```

2. **Configure Environment Secrets**:
   Copy `.env.example` to `.env` and provide your Google OAuth Web Client ID and backend server configurations:
   ```bash
   cp .env.example .env
   ```

3. **Build the Debug APK**:
   ```bash
   ./gradlew assembleDebug
   ```

4. **Run Unit & Robolectric Tests**:
   ```bash
   ./gradlew testDebugUnitTest
   ```

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>Is Vance Music completely free and ad-free?</b></summary>
<br>
Yes, Vance Music is 100% free and open-source. There are no built-in advertisements, commercial telemetry trackers, or subscription paywalls.
</details>

<details>
<summary><b>Can I listen to music offline?</b></summary>
<br>
Yes! Vance Music allows you to download individual songs, complete albums, and user playlists directly to device storage for offline playback without an active internet connection.
</details>

<details>
<summary><b>Does it support Android Auto and lock screen controls?</b></summary>
<br>
Yes. Thanks to the Media3 ExoPlayer implementation, Vance Music provides standard lock-screen media controls, Bluetooth audio metadata, and native Android Auto playback.
</details>

<details>
<summary><b>How are my passwords and tokens stored?</b></summary>
<br>
All sensitive tokens (OAuth ID tokens, access tokens, refresh tokens, and server passwords) are encrypted using AES-256 GCM with keys generated and stored in the hardware-isolated Android Keystore.
</details>

---

## 🌍 Supported Languages

Vance Music features comprehensive language preferences and localized content discovery:

| Language | Code | Content Discovery | UI Localization |
|:---|:---:|:---:|:---:|
| **English** | `en` | ✅ | ✅ |
| **Hindi (हिंदी)** | `hi` | ✅ | ✅ |
| **Punjabi (ਪੰਜਾਬੀ)** | `pa` | ✅ | ✅ |
| **Tamil (தமிழ்)** | `ta` | ✅ | ✅ |
| **Telugu (తెలుగు)** | `te` | ✅ | ✅ |
| **Spanish (Español)** | `es` | ✅ | ✅ |
| **French (Français)** | `fr` | ✅ | ✅ |
| **German (Deutsch)** | `de` | ✅ | ✅ |

---

---

## 👥 Contributors

A big thank you to all contributors who help make Vance Music better every day!

<p align="center">
  <a href="https://github.com/vance-music/vance-music/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=gokadzev/Musify" alt="Contributors" />
  </a>
</p>

---

## 📄 License

Vance Music is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the [LICENSE](LICENSE) file for more information.

```
Vance Music - Free, Open-Source Music Player for Android
Copyright (C) 2026 Vance Music Contributors

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
```

---

## ⚖️ Disclaimer

Vance Music does not host, own, or distribute any copyrighted audio content. The application acts as a clean client interface connecting to user-provided media servers (e.g., Navidrome, Subsonic) or public APIs. All product names, logos, and brands are property of their respective owners. Users are solely responsible for ensuring compliance with applicable copyright laws and regulations in their jurisdiction.
