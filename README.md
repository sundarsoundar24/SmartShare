# 🔗 SmartShare

**SmartShare** is a Python-based local network sharing application that allows you to instantly transfer files, text, and media between devices connected to the same Wi-Fi network. Designed with a lightweight Svelte frontend and FastAPI backend, it works seamlessly across desktop and mobile browsers — no internet required.

---

## 🚀 Features

- 📁 Transfer any file type across devices on the same LAN
- 🌐 Access via browser (`http://<your-local-ip>:8000`)
- 📄 Share clipboard text or media instantly
- 📡 Real-time device discovery via WebSocket
- 🔐 Optional PIN-based device pairing
- 🖥️ Cross-platform: works on desktop, phone, tablet
- 🧠 No external server or internet needed

---

## 🛠️ Tech Stack

- **Backend:** Python, FastAPI, WebSockets
- **Frontend:** Svelte / SvelteKit
- **Transport:** HTTP & WebSocket over local network

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/smartshare.git
cd smartshare
