# 👻 GhostChat — Private Offline Chat Rooms

> **Chat without internet. No network towers. Just WiFi.**

GhostChat is a real-time private chat application that works entirely over local WiFi or Mobile Hotspot — completely offline. No internet connection required, no SIM card, no cloud servers. Just people nearby, connected.

---

## 📸 Preview

| Connect Screen | Chat Screen | Website |
|---|---|---|
| Itachi Genjutsu themed intro | Real-time private rooms | Full landing page |

---

## ✨ Features

- 📡 **100% Offline** — Works over local WiFi or Mobile Hotspot only
- 🏠 **Private Rooms** — Create or join rooms with optional password protection
- 💬 **Real-Time Messaging** — Instant messages powered by Socket.io
- 😊 **Emoji Reactions** — Tap any message to react with 8 quick emojis
- ✏️ **Edit & Delete** — Edit or delete your own messages, syncs to all users
- 👤 **User Avatars** — Unique colored avatar for every user
- 🔔 **Sound Notifications** — Audio ping for new messages (toggle on/off)
- 🌙 **Light / Dark Theme** — Switch themes, preference saved automatically
- 🔄 **Auto-Reconnect** — Automatically reconnects if connection drops
- 💾 **Message History** — Last 300 messages stored per room
- 📥 **Unread Badges** — See unread message count per room
- 📱 **Cross-Platform** — Windows desktop + Android mobile, all connect together

---

## 📦 Downloads

| Platform | File | Version |
|---|---|---|
| 🪟 Windows | `GhostChat Setup 2.0.0.exe` | v2.0.0 |
| 🤖 Android | `ghostchat_mob.apk` | v2.0.0 |

> Download both from the [Releases page](https://github.com/g3175318-cmd/ghostchat/releases)

---

## 🚀 How It Works

GhostChat uses a **Host + Guest** model over a local network:

```
┌─────────────────────────────────────────────┐
│                                             │
│   Host (Windows PC)                         │
│   ├── Opens GhostChat Electron app          │
│   ├── Clicks "I will Be The Host"           │
│   ├── Server starts automatically           │
│   ├── Turns on Mobile Hotspot               │
│   └── Shares IP address with friends        │
│                                             │
│   Guests (Android / PC)                     │
│   ├── Connect to host's Hotspot             │
│   ├── Open GhostChat                        │
│   ├── Enter host's IP address               │
│   └── Start chatting! ✅                    │
│                                             │
│   Zero internet used at any point           │
└─────────────────────────────────────────────┘
```

> ⚠️ Enable **"Install from unknown sources"** in Android settings before installing.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Electron** | Windows desktop app wrapper |
| **Node.js** | Server runtime |
| **Express.js** | HTTP server |
| **Socket.io** | Real-time WebSocket communication |
| **Capacitor** | Android APK wrapper |
| **HTML/CSS/JS** | Frontend UI (no frameworks) |
| **BroadcastChannel API** | Same-device tab communication |

---

## 🌐 Website

The project includes a full landing website (`ghostchat-website.html`) with:

- 👁️ Itachi Uchiha Genjutsu themed intro animation
- 🐦 Flying crow animations & custom Sharingan cursor
- 🩸 Blood drip atmospheric effects
- 📥 Direct download buttons for Windows & Android
- 📖 Full how-to-use guide

---

## ⚠️ Known Limitations

- **Host must be on Windows** — the server runs inside the Electron desktop app
- **Same network required** — all devices must be on the same WiFi/Hotspot
- **Hotspot off = chat pauses** — if host's hotspot disconnects, chat stops until reconnected (auto-reconnect built in)
- **No message persistence** — messages are stored in memory; restarting the server clears history

---

## 🔮 Future Plans

- [ ] iOS support via Capacitor
- [ ] File/image sharing
- [ ] Voice messages
- [ ] Multiple host support
- [ ] Message encryption
- [ ] Offline peer-to-peer via WiFi Direct

---

## 👨‍💻 Developer

**Developed by Amlan Dey**

- GitHub: [@g3175318-cmd](https://github.com/g3175318-cmd)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

 ## 💰 You can help me by Donating
[![Support Me via UPI](https://img.shields.io/badge/Support_Me-UPI-6739B7?style=for-the-badge&logo=phonepe&logoColor=white)](https://support-me-fbhd.onrender.com)

---

<div align="center">

**👻 GhostChat — Connect without the world's network**

*"In this world, connection needs no towers, no signals, no internet — only proximity and will."*

</div>
