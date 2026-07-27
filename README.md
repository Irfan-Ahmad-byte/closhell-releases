<div align="center">

# 🐚 CloShell

### Secure SSH Terminal & Host Manager

*Connect, manage, and collaborate on SSH hosts — with encrypted sync across all your devices.*

[![Website](https://img.shields.io/badge/Website-closhell.clottis.net-blue?style=for-the-badge)](https://closhell.clottis.net)

</div>

---

## ✨ Features

- 🔐 **Encrypted Credential Sync** — SSH passwords & private keys encrypted with AES-256, synced across devices
- 🖥️ **Full Terminal Emulator** — xterm-256color with resize, copy/paste, and keyboard shortcuts
- 👥 **Team Collaboration** — Share hosts with your team using role-based access control
- 📁 **Host Groups** — Organize servers into logical groups
- 🔄 **Cross-Device Sync** — Your hosts follow you everywhere via CloShell Cloud or GitHub sync
- 📜 **Connection Logs** — Track SSH session history and team activity
- ⚡ **Command Snippets** — Save and reuse frequently used commands
- 🎨 **Beautiful Dark UI** — Modern, premium interface built with performance in mind

---

## 📥 Download

### Latest Release

| Platform | Download | Type |
|----------|----------|------|
| 🐧 **Linux** (Ubuntu/Debian) | [`.deb`](https://closhell.clottis.net/#download) | Installer |
| 🐧 **Linux** (Fedora/RHEL) | [`.rpm`](https://closhell.clottis.net/#download) | Installer |
| 🐧 **Linux** (Universal) | [`.AppImage`](https://closhell.clottis.net/#download) | Portable |
| 🪟 **Windows** | [`.msi`](https://closhell.clottis.net/#download) | Installer |
| 🪟 **Windows** | [`.exe`](https://closhell.clottis.net/#download) | NSIS Installer |

> 💡 **AppImage users**: Make it executable with `chmod +x CloShell_*.AppImage` then run it.

---

## 🚀 Getting Started

1. **Download** the installer for your platform from the [CloShell website](https://closhell.clottis.net/#download)
2. **Install** and launch CloShell
3. **Sign up** or log in with GitHub/Email
4. **Add your first host** — enter hostname, port, username, and credentials
5. **Connect** — click on a host to open an SSH terminal session

---

## 🔒 Security

- **AES-256-GCM** encryption for synced credentials
- **PBKDF2** key derivation with 100,000 iterations
- Credentials stored **locally** on your device, encrypted before sync
- Optional **master password** for end-to-end encryption
- **No plaintext** passwords or keys ever leave your machine unencrypted

---

## 🖥️ System Requirements

| | Minimum |
|--|---------|
| **Windows** | Windows 10 (64-bit) |
| **Linux** | Ubuntu 20.04+ / Fedora 35+ / Any with GTK3 + WebKit2GTK |
| **Memory** | 128 MB RAM |
| **Disk** | 100 MB |

---

## 🐛 Issues & Feedback

Found a bug or have a feature request? Email [support@clottis.net](mailto:support@clottis.net).

---

## 📄 License

CloShell is proprietary software by [Clottis](https://clottis.net). All rights reserved.

---

<div align="center">

**Built with ❤️ using [Tauri](https://tauri.app) + React + Rust**

[Website](https://closhell.clottis.net) · [Download](https://closhell.clottis.net/#download) · [Report Bug](mailto:support@clottis.net)

</div>
