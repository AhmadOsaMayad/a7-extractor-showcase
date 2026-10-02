<p align="center">
  <img src="assets/logo.png" alt="A7 Extractor" width="120">
</p>

<h1 align="center">A7 Extractor</h1>

<p align="center">
  <strong>Select. Extract. Done.</strong><br>
  Pull the exact pages you need out of any PDF — right on your phone.<br>
  No internet. No accounts. No uploads. Ever.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white" alt="Built with Flutter">
  <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white" alt="Android 7.0 or newer">
  <img src="https://img.shields.io/badge/languages-English%20%7C%20Arabic-4F46E5" alt="Languages: English and Arabic">
  <img src="https://img.shields.io/badge/privacy-100%25%20offline-16A34A" alt="100% offline">
  <img src="https://img.shields.io/badge/version-1.0.0-F97316" alt="Version 1.0.0">
</p>

---

**A7 Extractor** is a private, offline Android app built with Flutter. Pick a PDF, choose exactly the pages you want — individually, as a range, or all at once — and extract them into a brand-new document that keeps every page's original size and orientation.

This repository is the app's public home: **downloads, screenshots and documentation**. The application source is not distributed here.

## 📥 Download & install

| | |
| --- | --- |
| **APK** | [`a7_extractor-v1.0.0.apk`](release/a7_extractor-v1.0.0.apk) — 22.3 MB |
| **Version** | 1.0.0 (build 1) |
| **Requires** | Android 7.0 (API 24) or newer |
| **SHA-256** | `3b4d450d0ac33248038994b1f20e9ed5713136acd56b2856558c6ae835e14357` · [SHA256SUMS.txt](release/SHA256SUMS.txt) |

1. Download the APK above (on your phone, or transfer it over).
2. Allow installing from this source when Android asks — `Settings → Apps → Special access → Install unknown apps`.
3. Open the file, install, and start extracting.

> The build is debug-signed for direct installation and is not published on Google Play yet.

## ✨ What makes it different

| | |
| --- | --- |
| 🔒 **Truly offline** | The app declares no permissions at all — no `INTERNET`, no storage, no location. Your documents physically cannot leave the device. |
| 🎯 **Precision selection** | Tap two pages for a contiguous range, switch to individual mode for arbitrary sets, or take everything with one checkbox. |
| 🖼️ **See before you extract** | Every page is rendered live on-device, so you know exactly what you're taking with you. |
| 🧾 **Faithful output** | The extracted PDF preserves each source page's size and orientation — even in mixed portrait/landscape documents. |
| 🗂️ **Full file management** | Open, share, save-as, rename (with duplicate protection) and delete — without leaving the app. |
| 🌍 **English & Arabic** | Complete localization with full RTL layout, plus light and dark themes. |
| ⚡ **Polished UX** | Animated branded splash, guarded long-running extractions, pull-to-refresh, a cache summary with one-tap clearing, and clear empty states. |

## 📸 The journey, screen by screen

Every screenshot below was captured on a real device. The full gallery lives in [`screenshots/`](screenshots).

### 1 · Launch

| English | العربية |
| --- | --- |
| ![A7 Extractor splash screen in English](screenshots/splash-view-en.png) | ![A7 Extractor splash screen in Arabic](screenshots/splash-view-ar.png) |

### 2 · Your extraction hub

Pick a PDF, see every extracted file in one list, and check the app's cache usage — clear it with a single tap.

| English · light | English · dark | Cache & cleanup |
| --- | --- | --- |
| ![Home screen — English, light theme](screenshots/home-en-light.png) | ![Home screen — English, dark theme](screenshots/home-en-dark.png) | ![Home screen showing cache usage with the clear-cache action enabled](screenshots/home-clear-cache-texticon-is-enabled.png) |

### 3 · Pick a PDF

<p align="center">
  <img src="screenshots/broswing-storage-folders-after-onpick-file-button.png" alt="Android system file browser after tapping the pick-file button" width="260"><br>
  <sub>The Android system picker — your files never leave your device.</sub>
</p>

### 4 · Select exactly what you need

| Freshly picked | Range selection | Individual selection | Select all |
| --- | --- | --- | --- |
| ![Selection screen right after a PDF is picked](screenshots/init-selection-screen-after-file-is-picked-en-dark.png) | ![Contiguous range selection across pages](screenshots/selection-screen-range-selction-en-dark.png) | ![Individual page selection mode](screenshots/selection-screen-individual-selction-en-dark.png) | ![Select-all checkbox across every page](screenshots/selection-screen-select-all-en-dark.png) |

### 5 · Extract

| Working | Done | Read the result |
| --- | --- | --- |
| ![Extraction in progress with a busy overlay](screenshots/loading-indic-after-extract-button-ontap.png) | ![Extraction complete](screenshots/extraction-complete-after-extract-loading-indic.png) | ![The extracted PDF displayed on screen](screenshots/displaying-extracted-file.png) |

### 6 · Organize the results

| File actions | Rename | Renamed | Delete |
| --- | --- | --- | --- |
| ![Actions icon on an extracted file tile](screenshots/home-after-file-is-extracted-on-extracted-file-tile-options-icon.png) | ![Rename sheet for an extracted file](screenshots/rename-extracted-file-sheet.png) | ![Home screen after the extracted file was renamed](screenshots/home-after-extracted-file-is-renamed.png) | ![Delete confirmation dialog](screenshots/delete-extracted-file-alert-dialog.png) |

### 7 · Settings

| English · light | English · dark | العربية · light |
| --- | --- | --- |
| ![Settings — English, light theme](screenshots/settings-en-light.png) | ![Settings — English, dark theme](screenshots/settings-en-dark.png) | ![Settings — Arabic, light theme](screenshots/settings-ar-light.png) |

### 8 · Built for both languages and both moods

| EN · light | EN · dark | AR · light | AR · dark |
| --- | --- | --- | --- |
| ![Home — English, light](screenshots/home-en-light.png) | ![Home — English, dark](screenshots/home-en-dark.png) | ![Home — Arabic, light](screenshots/home-ar-light.png) | ![Home — Arabic, dark](screenshots/home-ar-dark.png) |

### 9 · About the developer

| Dark | Light |
| --- | --- |
| ![About the developer — dark theme](screenshots/about-developer-en-dark.png) | ![About the developer — light theme](screenshots/about-developer-en-light.png) |

## 🔐 Privacy by design

- **No permissions.** The shipped build declares zero permissions — no internet, no storage, no location, no camera.
- **Nothing to collect.** No accounts, no analytics, no ads, no trackers.
- **On-device only.** Page rendering, extraction and storage all happen locally.
- **You stay in control.** Extracted files live in the app's private folder until *you* choose to share or save them somewhere else.

## 🧱 Under the hood

| | |
| --- | --- |
| **Framework** | Flutter (Material 3) — one codebase, native-performance Android app |
| **PDF engine** | On-device page extraction and document assembly |
| **Page previews** | Native Android PDF rendering through a platform channel |
| **Design** | Responsive scaling from a 390×844 reference, full light & dark palettes |
| **Localization** | ARB-based message catalogs (English + Arabic) with complete RTL support |
| **Quality gates** | Static analysis and an automated test suite run on every change |

## 👤 Author

**Ahmad O. Mayad** — Mobile Application Developer (Flutter/Dart)

- GitHub: [AhmadOsaMayad](https://github.com/AhmadOsaMayad)
- Instagram: [a7mad_ousama](https://www.instagram.com/a7mad_ousama)
- Email: [ahmadosamayad@gmail.com](mailto:ahmadosamayad@gmail.com)

---

<p align="center"><sub>© 2026 Ahmad O. Mayad — all rights reserved. This repository hosts the official builds, screenshots and documentation of A7 Extractor.</sub></p>
