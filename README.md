# 🌌 Caelestia Notes

> A local-first, privacy-focused notes app for Android, built to integrate seamlessly with the **Vanilla Caelestia Shell**.

Caelestia Notes is the Android companion for the Caelestia ecosystem, providing a fast and beautiful notes experience while keeping your data local.

The app is designed to work independently on Android while also providing the required integration files for **Vanilla Caelestia Shell**, allowing the desktop environment to interact with and synchronize notes.

---

## ✨ Features

- 📱 Native Android notes application
- 🎨 Caelestia-inspired UI and design language
- 🔒 Local-first and privacy-focused
- 🗄️ Offline note storage
- 📶 Wi-Fi device-to-device synchronization
- 🔵 Bluetooth synchronization fallback
- 🔍 Automatic local device discovery
- 🔄 Conflict-aware synchronization
- 📌 Pinned notes
- 🎨 Note colors and themes
- 🌑 Caelestia theme support
- 🔗 Vanilla Caelestia Shell integration
- ⚡ Fast local synchronization without cloud services

---

# 📱 Android App

The primary purpose of this repository is the **Caelestia Notes Android application**.

The app is designed around a simple principle:

> **Notes should work offline, stay local, and sync directly between your devices.**

The Android application provides the complete notes experience, including creating, editing, organizing, and synchronizing notes.

---

## 🎨 Caelestia UI

Caelestia Notes follows the visual style of the Caelestia ecosystem.

The Android application will maintain a consistent design language across:

- Dashboard
- Notes
- Note editor
- Media
- Settings
- Sync interface
- Theme system

The goal is for the Android application to feel like a native part of Caelestia rather than a separate third-party companion app.

---

# 🔄 Synchronization

Caelestia Notes supports direct device-to-device synchronization.

No cloud database is required.

```text
┌──────────────────────┐
│   Android Device     │
│                      │
│  Caelestia Notes     │
└──────────┬───────────┘
           │
       Local Sync
           │
     ┌─────┴─────┐
     │           │
   Wi-Fi      Bluetooth
     │           │
     └─────┬─────┘
           │
┌──────────▼───────────┐
│  Vanilla Caelestia   │
│       Shell           │
└──────────────────────┘
