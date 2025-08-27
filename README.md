#  Nerv-IDE   

**Nerv-IDE** is a **real-time collaborative code editor** that empowers developers to seamlessly work together.  
Multiple users can enter a room, share a unique Nerv-Room ID, and collaborate on code simultaneously — with live chat, drawing, syntax highlighting, and even an **AI-powered copilot**.  

🌍 **Repo:** [Nerv-IDE](https://github.com/kenxpx/Nerv-IDE)  

---

## ✨ Features  

- 💻 **Real-time collaboration** across multiple files  
- 📁 File & folder management: create, open, save, delete, and organize projects  
- 💾 Download the **entire project** as a ZIP archive  
- 🚀 **Unique room generation** with Nerv-Room IDs  
- 🌈 Syntax highlighting with **auto-language detection**  
- ⚡ **Code execution** inside the IDE  
- 🔔 Notifications for user join/leave events  
- 👥 Real-time **user presence dashboard**  
- 💬 Built-in **chat system** for communication  
- 🎩 Hover **tooltips** showing who is editing what  
- 🖊 Live **cursor tracking & text selection highlights**  
- 🤖 **AI Copilot**: generate, replace, or fix code instantly  
- 🎨 **Themes & font customization** for a personalized experience  
- ✏️ **Collaborative drawing** canvas for brainstorming  

---

## ⚙️ Tech Stack  

- **Frontend:** React + TypeScript + TailwindCSS + React Router  
- **Backend:** Node.js + Express.js + Socket.IO  
- **Deployment:** Vercel + Docker  
- **Version Control:** Git + GitHub  

---

## 🚀 Installation  

### Method 1: Manual  

```bash
# Clone Nerv-IDE
git clone https://github.com/kenxpx/Nerv-IDE.git

# Install dependencies (both client + server)
npm install
```

Setup **.env** files:  

**Frontend (`client/.env`)**
```
VITE_BACKEND_URL=<your_server_url>
```

**Backend (`server/.env`)**
```
PORT=3000
```

Run locally:  

```bash
# Frontend
cd client
npm run dev

# Backend
cd server
npm run dev
```

Access --> [http://localhost:8080](http://localhost:5173/)  

---

### Method 2: Docker  

```bash
# Run Backend
docker run -d -p 3000:3000 --name nerv-ide-server kenxpx/nerv-ide-server:latest  

# Run Frontend
docker run -d -p 5173:5173 --name nerv-ide-client kenxpx/nerv-ide-client:latest  
```

---

## 🌌 Roadmap  

- 🔑 Admin Permissions — manage user access & room controls  
- 🕹️ Anime-inspired **UI themes** (Nerv HQ console, MAGI System, etc.)  
- 📡 Collaboration history & playback  

---

## 🤝 Contributing  

Contributions are welcome.  
Fork → Commit → PR → Merge ✅  

---

## 🧾 License  

This project is licensed under the **MIT License**.  

---

## 👨‍💻 Developer  

**Author:** [Kenxpx](https://github.com/Kenxpx)  
Building futuristic, collaborative, and open-source tools.  

---

## 🌟 Appreciation  

Special thanks to open-source projects that power Nerv-IDE:  
- [Piston API](https://github.com/engineer-man/piston) — Code execution  
- [tldraw](https://github.com/tldraw/tldraw) — Collaborative drawing  

---

🔥 *Nerv-IDE — mission control for your collaborative coding.* 🚀  
