# LogicLayer

[![GitHub](https://img.shields.io/github/license/varshu2024/LogicLayer?style=for-the-badge&color=48bf21)](https://github.com/varshu2024/LogicLayer)
[![GitHub Stars](https://img.shields.io/github/stars/varshu2024/LogicLayer?style=for-the-badge&color=d7af2d)](https://github.com/varshu2024/LogicLayer/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/varshu2024/LogicLayer?style=for-the-badge&color=f47373)](https://github.com/varshu2024/LogicLayer/issues)

**LogicLayer** is a high-performance, real-time collaborative development suite designed for modern engineering teams. It merges seamless code synchronization with a rich creative canvas and AI-driven intelligence, providing an all-in-one environment for brainstorming, architecting, and building complex systems.

---

### 🌐 [Live Demo: LogicLayer Platform](https://logiclayer-1.onrender.com)
*   **Frontend**: [logiclayer-1.onrender.com](https://logiclayer-1.onrender.com)
*   **Backend Server**: [logiclayer-server.onrender.com](https://logiclayer-server.onrender.com)

---

## 🚀 Core Functional Pillars

### ⚡ Real-Time Synergy
- **Low-Latency Synchronization**: Experience instantaneous code updates across all participants powered by optimized WebSocket protocols and CodeMirror 6.
- **Presence Intelligence**: Live indicators showing active collaborators, their cursors, and real-time selections for maximum context awareness.
- **Integrated Comms**: Built-in high-fidelity chat for seamless communication without leaving the development environment.

### 🤖 Intelligent Execution
- **AI Copilot**: An advanced assistant for code generation, refactoring, and logic explanation, helping teams move from idea to implementation faster.
- **Universal Code Execution**: Integrated with the Piston API to allow multi-language code execution directly within the workspace.
- **Intelligent Autocomplete**: Context-aware suggestions tailored to the project's programming language and architecture.

### 🎨 Creative & File Suite
- **Collaborative Whiteboard**: An infinite canvas powered by Tldraw for system design, sketching, and architectural planning.
- **Advanced File Management**: Full CRUD capabilities for complex directory structures with instant synchronization across the team.
- **One-Click Export**: Capability to download the entire codebase as a structured ZIP archive for offline use or deployment.

---

## 🛠 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Frontend** | React 18, TypeScript, Tailwind CSS, Vite |
| **Backend** | Node.js, Express, Socket.io |
| **Core Libraries** | CodeMirror 6, Tldraw, File-Saver |
| **Infrastructure** | Docker, Docker Compose |

---

## ⚙️ Deployment & Setup

### Environment Configuration
Configure your environment by creating `.env` files in the respective directories:

**Frontend Configuration (`/client/.env`)**:
```bash
VITE_BACKEND_URL=your_server_url
VITE_PISTON_API_URL=your_piston_api_url
```

**Backend Configuration (`/server/.env`)**:
```bash
PORT=3000
```

### Manual Installation
1. **Repository Setup**:
   ```bash
   git clone https://github.com/varshu2024/LogicLayer.git
   cd LogicLayer
   ```
2. **Install Dependencies**:
   Run `npm install` in both the `client` and `server` directories.
3. **Start Development Servers**:
   - Backend: `cd server && npm run dev`
   - Frontend: `cd client && npm run dev`

### Containerized Setup (Docker)
Ensure Docker Desktop is installed and running:
```bash
docker compose up -d
```
Access the application at `http://localhost:5173`.

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.


