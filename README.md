# EaglePort OS Launcher

A lightweight Android home launcher (`com.eagleport.launcher`) designed for smooth performance on entry-level devices such as the **Tecno POP 5 Go** (1 GB RAM, 16 GB storage, 480×960 display, Android 11)[cite: 6, 7].

## Features

* **Home Screen & Glass UI:** Top header with **EaglePort OS Launcher** branding, quick notification/alerts and settings buttons, a search bar (*"Search locally or swipe up for apps"*), a clock & date card, a weather card (`28°C`, `Partly Cloudy`, high/low temperatures), multi-page home indicator dots, and a bottom dock[cite: 6, 8].
* **App Library:** Dedicated app drawer with instant app search (*"Search apps..."*), hexagonal app icons, and gesture hints (swipe up from home to open the App Library, swipe left on home to open launcher settings)[cite: 9].
* **Device Center / Phone Status:** Quick overview screen displaying battery percentage and estimated time remaining, device info (`Tecno POP 5 Go`), telemetry cards for temperature, memory, storage, and CPU load, plus a recent app activity list with dismiss controls[cite: 7].
* **Built-In Navigation Bar Controls:** Bottom navigation bar with **Back**, **Home**, and **Recents** actions[cite: 8, 9].
* **Lightweight for Low-RAM Devices:** Built with `minSdk 26` and `targetSdk 35` to keep UI overhead manageable on 1 GB RAM hardware[cite: 7].

## Project & Build Info

* **Package / Namespace:** `com.eagleport.launcher`
* **SDK Targets:** `minSdk 26` / `targetSdk 35` (`compileSdk 35`, Java 17)
* **CI & Releases:** Built via GitHub Actions (`Android debug build`) and distributed as `app-debug.apk` / `EaglePortOs.apk`[cite: 2, 4].

## Installation

1. Download the `.apk` file from **Releases** (or extract it from your workflow artifact).
2. Transfer the `.apk` to your Android phone (for example, into the `Download` folder).
3. Tap the `.apk` file, allow installing from unknown apps if prompted, and tap **Install**.
4. Press **Home** or open your Android **Settings > Apps > Default apps > Home app** to select **EaglePort OS Launcher**.