# README.md
Klarinet_Trading Bot
<p align="center">
  <img src="https://github.com/klarinetchilas/trading-assistant/assets/logo.png" alt="Trading Assistant Logo" width="150"/>
</p>

<h1 align="center">📈 Trading Assistant – KLARINET ROYAL CHILAS</h1>

<p align="center">
  <a href="https://github.com/klarinetchilas/trading-assistant/actions/workflows/flutter-release.yml">
    <img src="https://github.com/klarinetchilas/trading-assistant/actions/workflows/flutter-release.yml/badge.svg" alt="Build Status">
  </a>
  <a href="https://github.com/klarinetchilas/trading-assistant/releases/latest/download/app-release.apk">
    <img src="https://img.shields.io/badge/⬇️_Download_Latest_APK-blue" alt="Download Latest APK">
  </a>
</p>

---

## 🧠 About the App

**Trading Assistant** is a smart AI-powered Android bot developed by **KLARINET ROYAL CHILAS**.  
It helps users **automate and optimize their trades on the IQ Options platform**, monitor profits, and manage strategies safely — all from one place.  

Designed for speed, accuracy, and simplicity, it brings professional-grade automation tools to everyday traders.

---

## 🌟 Key Features

✅ **Automated IQ Option Trades** — executes trades based on your preset strategy and signals.  
✅ **Smart Risk Management** — dynamically adjusts trade size according to balance.  
✅ **Real-time Monitoring** — tracks profit/loss and strategy performance live.  
✅ **Trade History Dashboard** — clean UI with daily/weekly stats.  
✅ **Alerts & Notifications** — email and push alerts for key events.  
✅ **Manual Override** — pause, resume, or manually control trades anytime.  
✅ **Cloud Backup** — stores preferences and sessions securely.  

---

## 🧩 Tech Stack

| Layer | Technology Used |
|--------|----------------|
| App Framework | **Flutter (Dart)** |
| Backend Automation | **Python + FastAPI / Flask** |
| Trading API | **IQ Option WebSocket** |
| CI/CD | **GitHub Actions** |
| Deployment | **Google Play Console** |
| Notifications | **Gmail SMTP + Push Alerts** |

---

## 📦 Installation

1. Download the latest APK from here 👇  
   [![Download](https://img.shields.io/badge/⬇️_Download_Latest_APK-blue)](https://github.com/klarinetchilas/trading-assistant/releases/latest/download/app-release.apk)

2. On your Android device:
   - Go to **Settings → Security → Allow installation from unknown sources**
   - Tap the downloaded file and install.

3. Launch the app, connect your IQ Option account, and set your strategy.

---

## 🧰 Development Setup

If you want to build or customize the bot:

```bash
git clone https://github.com/klarinetchilas/trading-assistant.git
cd trading-assistant
flutter pub get
flutter run
