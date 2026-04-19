# ⏱️ Simple IF Tracker

A lightweight, privacy-focused **Intermittent Fasting & Water Tracker** web app.Zero dependencies, single-file, fully installable as a PWA, and works completely offline.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-green.svg)](https://web.dev/progressive-web-apps/)
[![Vanilla JS](https://img.shields.io/badge/JS-Vanilla-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## ✨ Features

* 🕒 **Smart Fasting Timer** – Count Up or Count Down with real-time progress & hour markers
* 📊 **Preset Protocols** – 12:12, 14:10, 16:8, 18:6, 20:4, 23:1 (OMAD) + fully customizable **FLEX** hours
* 💧 **Water Intake Tracker** – Set daily targets, quick-add buttons, auto-resets at midnight
* 📜 **Collapsible History & Stats** – Editable notes, weekly analytics (total fasts, avg duration, completion rate), and **CSV export**
* 🔔 **Dual Notifications** – In-app toasts (work without browser permissions) + optional native system alerts
* 🔊 **Audio & Haptic Feedback** – Milestone chimes & mobile vibration
* 🌙 **Dark/Light Mode** – System-aware with manual toggle & persistent preference
* 📲 **Fully Installable PWA** – Add to home screen, works offline, background service worker
* 🔒 **100% Private** – All data stored locally. No accounts, no tracking, no external servers

## 🚀 How to Use

### 🖥️ Local Use

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. *(Optional)* Run a local server for full PWA support: `python -m http.server` or `npx serve`

### ☁️ Live Demo

[Click here to try it live](https://vojislav77.github.io/if-tracker/if-tracker.html target="_blank")

### 📱 Install as App

* **Android**: Chrome → `⋮` → `Add to Home screen`
* **iOS**: Safari → `Share` → `Add to Home Screen`
* **Desktop**: Click the install icon in your browser's address bar

## 🛠️ Tech Stack

* **HTML5** / **CSS3** (Variables, Flexbox/Grid, Smooth Transitions)
* **Vanilla JavaScript** (ES6+, Web Audio API, Vibration API, Service Workers)
* **LocalStorage** for persistent state & preferences
* **Zero Dependencies** – No frameworks, no build steps, no external APIs

## 🔒 Privacy & Offline Support

* All fasting logs, water intake, notes, and UI preferences are stored **locally in your browser**
* No internet connection required after first load
* Zero analytics, trackers, or third-party scripts
* Works seamlessly on `localhost`, `file://`, or any static host

## 📄 License

This project is licensed under the [MIT License](LICENSE). Free to use, modify, and distribute.

* * *

💡 *Built for simplicity, speed, and your health. Stay hydrated & fast strong!* 💧⏱️
