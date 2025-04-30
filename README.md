# 🧑‍💻 Real-Time Collaborative Code Editor

Developed an online tool enabling collaborative code writing, editing, and review for multiple users using JavaScript. 

Integrated support for multiple programming languages with syntax highlighting and version tracking.  

Implemented communication features to enhance team collaboration and productivity.    

You can visit here   
      
https://codebuddytextedit.netlify.app/
 

---


A full-stack, browser-based code editor enabling real-time collaboration among multiple users—built with performance, resilience, and developer-first UX in mind.

---

## 🚀 Overview
This project simulates a Google Docs-like experience for code—multiple users can write, edit, and view code together in real-time, complete with syntax highlighting, persistent sessions, and a responsive UI.

Developed as a personal passion project to explore concurrency, WebSockets, and real-world system reliability outside the academic curriculum.

---

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Real-Time Layer:** WebSockets (Socket.io)
- **Database:** MongoDB (session persistence)
- **Other Tools:** GitHub Actions. 

---

## ✨ Features
- 🔁 **Real-Time Sync**: Edits are instantly reflected across all connected users  
- 🧠 **User Presence**: Visual indicators of active collaborators  
- 🎨 **Syntax Highlighting**: Supports multiple languages using CodeMirror or Monaco (depending on your setup)  
- 🧘‍♀️ **Resilient Architecture**: Reconnection handling prevents code loss  
- 📱 **Responsive Design**: Usable across desktop, tablet, and mobile  

---

## 📷 Demo

> Real-time collaboration with 2+ users editing the same document simultaneously.

---

## 🧪 Challenges Tackled
- Designed a fault-tolerant WebSocket system that gracefully handles disconnects and reconnections  
- Implemented state reconciliation logic to avoid data conflicts  
- Optimized WebSocket events to minimize latency and bandwidth usage  
- Built a frontend that mimics the simplicity of an IDE with zero setup

---

## 🌍 Use Cases
- Pair programming
- Remote coding interviews
- Hackathons
- Online teaching or mentoring

---

## 🔐 Security Considerations
- Input sanitization to prevent XSS  
- Server-side validation for all critical events  
- Plans to add user authentication and access control

---

## 📈 Future Improvements
- Support for multiple file tabs and file uploads  
- Terminal integration for running code  
- Authentication (OAuth, JWT)  
- Deploy to public cloud (AWS/Render/Vercel) with CI/CD

---

## 👨‍💻 Author
**[Antim Maurya]** – | [https://github.com/Antim21/Real-time-Code-Editor](#)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---


**Tech Stack**

Frontend: React.js, CSS, HTML

Backend: Node.js, Express.js

WebSocket Protocol: Socket.IO for real-time communication

Code Parsing: Integrated with Ace Editor or CodeMirror for code editing

Database: MongoDB (for storing user session and code history)
