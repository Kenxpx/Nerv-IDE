# Nerv-IDE

**Nerv-IDE** is a next-generation **real-time collaborative code editor** that makes pair programming, group projects, and coding sessions seamless. Multiple developers can join the same room, share code, chat, draw, and even use an **AI-powered copilot** — all in the browser.

🔴 **Live Demo:** [nervide.sachinbind.net](https://nervide.sachinbind.net/)  
📦 **Docker Images:** `sachinxps/nerv-ide-server` · `sachinxps/nerv-ide-client`

---

## ✨ Key Features

- ⚡ **Realtime collaboration** with shared rooms
- 💬 Built-in **chat** and **presence tracking**
- 👥 See who’s editing — with live **cursor & selection highlights**
- 📂 File/folder management: create, edit, delete, and save
- 💾 Export projects as **ZIP downloads**
- 🎨 Customizable themes & fonts
- 🖊 Collaborative **drawing board**
- 🤖 **AI Copilot** for instant code generation/fixes
- 🚀 **Code execution** powered by [Piston](https://github.com/engineer-man/piston)

---

## 🛠 Tech Stack

- **Frontend:** React · TypeScript · TailwindCSS · React Router  
- **Backend:** Node.js · Express · Socket.IO  
- **Infra:** Docker · Free hosting via Render (API) + Hostinger (Frontend)  
- **Extras:** Piston API, tldraw library

---

## 🚀 Getting Started

### Run locally (manual)
```bash
# Clone
git clone https://github.com/Kenxpx/Nerv-IDE.git
cd Nerv-IDE
```

**Frontend `.env`**
```
VITE_BACKEND_URL=http://localhost:3000
```

**Backend `.env`**
```
PORT=3000
```

**Start backend**
```bash
cd server
npm install
npm run dev
```

**Start frontend (new terminal)**
```bash
cd client
npm install
npm run dev
```

Visit → http://localhost:5173

---

### Run with Docker (one-liners)
```bash
docker run -d -p 3000:3000 -e ALLOWED_ORIGINS=http://localhost:5173 --name nerv-ide-server sachinxps/nerv-ide-server:latest

docker run -d -p 5173:5173 --name nerv-ide-client sachinxps/nerv-ide-client:latest
```

➡️ For production: use `sachinxps/nerv-ide-client:prod` (pre-built with hosted API URL).

---

## 🌐 Deployment Example (Free Setup)
- **Backend** → [Render](https://render.com/) (free web service from Docker image)
- **Frontend** → [Hostinger](https://hostinger.com/) (upload `/client/dist` build)
- **Domains** → Custom subdomains: `api.nervide.sachinbind.net` + `nervide.sachinbind.net`

---

## 🤝 Contributing

Contributions are welcome!  
Fork → Branch → Commit → PR → Merge ✅

---

## 📜 License

Released under the **MIT License**.

---

## 👨‍💻 Author

Built by [Kenxpx](https://github.com/Kenxpx) · Dockerized & hosted by [Sachinxps](https://hub.docker.com/u/sachinxps)
