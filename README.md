# CodeAlpha Projects 🚀

A collection of three full-stack web application projects built as part of internship program.

---

## Projects

| # | Project | Description | Stack |
|---|---|---|---|
| 1 | [Codealpha_communication](#1-codealpha_communication) | Real-time video communication platform | React, Node.js, WebRTC, Socket.io, MongoDB |
| 2 | [Codealpha_social2026](#3-codealpha_social2026) | Lightweight social media platform | Vanilla JS, Node.js, Express, MySQL |

---

## 1. Codealpha_communication

> 📁 `Codealpha_communication/` — [Full README](./Codealpha_communication/README.md)

**RealConnect** is a real-time video communication platform where users can create or join rooms for multi-party video calls, chat, file sharing, and collaborative whiteboarding.

### Key Features
- 📹 Multi-user WebRTC peer-to-peer video & audio calls
- 🖥️ Screen sharing
- 💬 Real-time in-room chat with persistent history (MongoDB)
- 📎 File sharing up to 2MB via Socket.io
- 🎨 Collaborative whiteboard with pen, brush, spray & eraser tools
- 📨 User-to-user room invitations
- 🔐 JWT authentication (7-day token)

### Tech Stack
- **Frontend:** React 19, Vite, Socket.io Client, Simple-Peer, Framer Motion, Tailwind CSS
- **Backend:** Node.js, Express, Socket.io, MongoDB + Mongoose, bcryptjs, JWT

---

## 2. Codealpha_social2026

> 📁 `Codealpha_social2026/` — [Full README](./Codealpha_social2026/README.md)

**Social 2026** is a lightweight social media platform with no frontend framework — just vanilla HTML/CSS/JS served directly by Express, backed by MySQL.

### Key Features
- 📝 Global post feed — create & view all posts
- ❤️ Like / unlike posts with live count updates
- 💬 Inline comments on posts
- 👤 User profiles with followers/following counts
- 👥 Follow / unfollow other users
- 🔍 Live debounced user search in the navbar
- 🔐 Session-based auth (24-hour, stored in MySQL)
- 🛡️ XSS protection on all user content

### Tech Stack
- **Frontend:** Vanilla HTML/JS (Fetch API), Tailwind CSS v4 (CDN), Font Awesome 6 (CDN)
- **Backend:** Node.js, Express, MySQL2, express-session, express-mysql-session


## Repository Structure

```
Codealpha_Tasks/
├── README.md                          # This file
├── Codealpha_communication/           # RealConnect — WebRTC video platform
│   ├── README.md
│   ├── client/                        # React + Vite frontend
│   └── server/                        # Node.js + Socket.io backend
└── Codealpha_social2026/              # Social 2026 — social media platform
    ├── README.md
    ├── server.js                      # Node.js + Express server
    └── public/                        # Vanilla HTML frontend pages
```

---

## Common Prerequisites

- **Node.js** v18+
- **MySQL** (for `Codealpha_social2026`)
- **MongoDB** / MongoDB Atlas (for `Codealpha_communication`)
