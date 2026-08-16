# SYSTEM_LIMIT_/ // Habit Tracker & Protocol Engine

A cyberpunk-inspired, production-ready Progressive Web Application (PWA) and native Android application engineered for high-density daily habit management, visual streak tracking, and personal protocol enforcement.

---

## 🚀 Live Environments & Mobile Deployment

* **Web / PWA Application:** https://szymon-gabriel.github.io/system-limit
* **Native Android Build:** Compiled via Capacitor (APK ready for mobile execution).

---

## 🧠 Engineered Features & Core Architecture

* **Native Mobile Integration (Capacitor):** Fully configured Android native runtime environment with adaptive launcher iconography and native device shell integration.
* **Progressive Web App (PWA) Support:** Offline-first architecture, `manifest.json` launcher hooks, and service worker caching for direct web installation.
* **Dark Cyber / Glassmorphism UI:** Built with custom high-contrast color palettes (`#050206` base, `#ff1a43` neon accents) and blur mechanics for optimal visual hierarchy.
* **Persistent Local State Management:** Native client-side storage architecture ensuring zero data latency, instant habit toggles, and multi-session persistence without external dependencies.
* **Custom SVG Brand Integration:** Handcrafted geometric monogram visual assets with dynamic CSS filters and adaptive system icon density.

---

## 🏗️ Repository Directory Layout

* `index.html` - Primary interface structural layer, CSS design tokens, and application logic.
* `manifest.json` - PWA configuration layer defining viewport display parameters and metadata.
* `capacitor.config.json` - Native Capacitor runtime configuration and Android build settings.
* `android/` - Native Android Studio project structure and Gradle build scripts.
* `www/` - Compiled distribution directory for cross-platform deployment.
* `README.md` - System architecture documentation and deployment overview.

---

## ⚙️ Core Technology Stack

* **Frontend:** HTML5, CSS3 (Custom Variables, Glassmorphism Filters), Modern JavaScript (ES6+).
* **Cross-Platform / Mobile:** Capacitor Framework (`@capacitor/core`, `@capacitor/android`).
* **Platform Support:** Web PWA, Android Native App (APK).