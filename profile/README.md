<div align="center">

# 🌱 GraceThings

**Crafting thoughtful, native, and privacy-respecting Android tools.**

<br/>

[![Kotlin](https://img.shields.io/badge/Kotlin-2.0+-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Platform-Android_11+-3DDC84?style=flat-square&logo=android&logoColor=white)](https://www.android.com/)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Material 3](https://img.shields.io/badge/Design-Material_You_(M3)-blueviolet?style=flat-square&logo=materialdesign&logoColor=white)](https://m3.material.io/)
[![Local First](https://img.shields.io/badge/Architecture-Local--First-success?style=flat-square&logo=sqlite&logoColor=white)](#-our-philosophy)
[![Open Source](https://img.shields.io/badge/Open_Source-❤️-red?style=flat-square)](#)

<br/>

**[English](README.md)** | **[中文说明](README-CN.md)**

</div>

---

## 🌿 About GraceThings

At **GraceThings**, we build modern, lightweight, and privacy-first Android applications. We believe that great tools should:

- **Respect Your Attention & Privacy**: Zero ads, zero third-party telemetry or trackers, and no aggressive background behavior.
- **Embrace Native Android Ecosystem**: Designed around modern guidelines (Jetpack Compose & Material You), unlocking native system capabilities without requiring Root or Shizuku.
- **Guarantee Complete Data Sovereignty**: Grounded in a strict **Local-First** architecture—all your personal records remain on your device, complemented by transparent, offline backup and restore.

---

## 🚀 Featured Projects

<div align="center">

| Project | Category | Key Highlights | Availability |
| :--- | :--- | :--- | :--- |
| **[Bubble Notice](#-bubble-notice)** | Floating Bubble & Notification Hub | System floating bubbles, smart stacking, no Root/Shizuku, fullscreen friendly | [![Google Play](https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=io.github.gracethings.bubblenotice) [![F-Droid](https://img.shields.io/badge/F--Droid-1976D2?style=flat-square&logo=f-droid&logoColor=white)](https://f-droid.org/en/packages/io.github.gracethings.bubblenotice/) [![GitHub](https://img.shields.io/badge/GitHub-Releases-black?style=flat-square&logo=github)](https://github.com/GraceThings/bubble-notice-android/releases) |
| **[Pixel World](#-pixel-world)** | Real-world Footprint & Fog Explorer | Dual-precision tracking, smart activity sleep, OSM boundary integrals, offline tiers | [![Google Play](https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.velviagris.adventure) [![Releases](https://img.shields.io/badge/GitHub-Releases-black?style=flat-square&logo=github)](https://github.com/GraceThings/pixel-world-releases/releases) [![Issues](https://img.shields.io/badge/Report-Issues-orange?style=flat-square&logo=github)](https://github.com/GraceThings/pixel-world-releases/issues) |
| **[SuiDays](#-suidays)** | Minimalist Solar & Lunar Countdown | Material 3 dynamic color, Gregorian & Lunar engines, system calendar sync | [![Google Play](https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=io.github.gracethings.suidays) [![MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/GraceThings/suidays) [![GitHub](https://img.shields.io/badge/Repo-SuiDays-black?style=flat-square&logo=github)](https://github.com/GraceThings/suidays) |

</div>

<br/>

### 💬 [Bubble Notice](https://github.com/GraceThings/bubble-notice-android)
> **Lightweight Bubble Notifications & Central Console for Android 11+**

A lightweight notification enhancement tool providing an intuitive floating experience for the Multitasking 'Bubbles' feature in Android 17 and lower versions (Android 11+), **with no Root or Shizuku required**.

* 🔔 **System-Level Floating Bubbles**: Freely subscribe to your most-used apps and enjoy persistent, interactive message bubbles that keep important conversations accessible.
* 📦 **Smart Stacking & Expansion**: Intelligently groups consecutive notifications from the same app; keeps things tidy in a compact preview and expands smoothly to display full context and actions.
* ⚡ **Inherited Quick Actions**: Extracts native notification actions (such as *Mark as Read* or *Reply*) to let you respond directly within the floating panel.
* 🚀 **One-Tap App Jump**: Tap any unread message card or bubble notification to navigate straight to the specific chat or page.
* 🎛️ **Unified Notification Console**: Browse, inspect, and manage all your unread messages in one centralized dashboard.
* 🛡️ **Distraction-Free & Fullscreen Aware**: Automatically conceals itself during fullscreen media playback and games; easily summoned via edge swipe or dismissed with a quick flick.

🔗 **Quick Links**:  
[GitHub Repository](https://github.com/GraceThings/bubble-notice-android) · [Google Play](https://play.google.com/store/apps/details?id=io.github.gracethings.bubblenotice) · [F-Droid](https://f-droid.org/en/packages/io.github.gracethings.bubblenotice/) · [Latest Releases](https://github.com/GraceThings/bubble-notice-android/releases)

---

### 🌍 [Pixel World](https://github.com/GraceThings/pixel-world-releases)
> **Location-based "Fog of World" Footprint Tracker & Trajectory Chronicler**

Pixel World divides the globe into millions of micro-grids, silently chronicling your real-world journeys in the background and lifting the "fog of the unknown" as you move across streets, cities, and countries.

* 🗺️ **Dual-Precision Tracking Engine**:
  * **📍 Precise Mode (Zoom 18)**: Street-level resolution ideal for city walking tours, jogging, and outdoor hiking.
  * **🔋 Battery Saver Mode (Zoom 14)**: District-level low-power grid tracking, perfect for daily commutes, highway road trips, and high-speed rail.
* 🔋 **Smart Activity Hibernation**: Integrated with Google Activity Recognition. When you remain still, GPS location requests automatically sleep; the moment you begin moving, tracking wakes up seamlessly.
* 🏙️ **Authentic Administrative Boundaries & Spherical Integrals**: Fetches official administrative GeoJSON boundaries via OpenStreetMap Nominatim. Uses spherical polygon area line integrals rather than crude bounding boxes to calculate exact square kilometers explored.
* 🏆 **Offline Achievement Engine**: Automatically unlocks tier badges from Bronze to Onyx (*Earth Walker*, *Globetrotter*, *Pathfinder Fever*). A daily summary is pushed at 21:00 via WorkManager detailing your progress.
* 🗄️ **Complete Data Sovereignty**: Stored 100% locally with Room Database. Includes one-click JSON backup/restore and built-in diagnostic logging.

🔗 **Quick Links**:  
[Releases Repository](https://github.com/GraceThings/pixel-world-releases) · [Google Play](https://play.google.com/store/apps/details?id=com.velviagris.adventure) · [Bug Reports & Feedback](https://github.com/GraceThings/pixel-world-releases/issues)

---

### 🗓️ [SuiDays](https://github.com/GraceThings/suidays)
> **Modern, Privacy-Focused Solar & Lunar Countdown Application**

A clean, modern countdown and anniversary companion built with Jetpack Compose and Material 3 design principles, crafted to preserve life's meaningful moments without ads or trackers.

* 🎨 **Material 3 & Dynamic Color**: Fully embraces Material You with automatic wallpaper color extraction and native dark mode support.
* 🌙 **Gregorian & Chinese Lunar Calendars**: Comprehensive support for solar dates as well as traditional lunar birthdays and festivals (powered by `lunar-java`).
* 🔄 **Flexible Recurrence & Smart Reminders**: Schedule events to repeat daily, weekly, monthly, or yearly, complete with multi-day advance alerts and system alarm integration.
* 📅 **System Calendar Sync**: Bidirectional integration with Android's system calendar keeps your schedule unified.
* 🖼️ **Aesthetic Share Cards**: Generate high-resolution, beautifully styled countdown poster cards ready for saving or social sharing.
* 🔒 **Offline-First & Fully Open Source**: Zero ads, zero trackers, and zero telemetry. Complete JSON export and merge-back support.

🔗 **Quick Links**:  
[GitHub Repository](https://github.com/GraceThings/suidays) · [Google Play](https://play.google.com/store/apps/details?id=io.github.gracethings.suidays) · [MIT License](https://github.com/GraceThings/suidays/blob/master/LICENSE)

---

## 💡 Our Philosophy
