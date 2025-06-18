
# Connectly 💬

**Connectly** is a full-stack real-time web application that enables users to chat, share files, and make video calls securely and efficiently.

> 🔧 Built with: **React**, **Vue**, **TailwindCSS**, **Node.js**, **Express**, **MongoDB**, **Socket.IO**, and **WebRTC**

---

## 🚀 Features

- ✅ **1-on-1 & Group Chat** with real-time updates
- 📂 **File Sharing** (images, PDFs, docs, etc.)
- 🎥 **Video Calling** using WebRTC
- 🧑‍🤝‍🧑 **User Authentication & Authorization**
- 🌐 **Responsive UI** built with TailwindCSS
- 🔒 **Secure Communication** with HTTPS and socket encryption
- 🧭 **Online Presence & Typing Indicators**

---

## 🖥️ Tech Stack

| Frontend     | Backend        | Realtime       | Database    |
|--------------|----------------|----------------|-------------|
| React / Vue  | Node.js, Express | Socket.IO       | MongoDB (Atlas) |
| TailwindCSS  | REST API       | WebRTC (video) | Mongoose    |

---

## 📁 Project Structure

```
connectly/
├── backend/          # Express server, APIs, socket logic
│   ├── routes/
│   ├── controllers/
│   └── models/
├── client/           # Frontend (React or Vue)
│   ├── components/
│   ├── pages/
│   └── hooks/
├── docker-compose.yml
├── Jenkinsfile
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/subhadeepdutta12/connectly.git
cd connectly
```

### 2. Setup Environment Variables

Create `.env` files in both `/backend` and `/client` directories:

#### `/backend/.env`
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017
```

#### `/client/.env`
```env
VITE_API_URL=http://localhost:5000
```

---

### 3. Run the App Locally

#### 🚀 Backend
```bash
cd backend
npm install
npm run dev
```

#### 💻 Frontend
```bash
cd client
npm install
npm run dev
```

Now go to: [http://localhost:5173](http://localhost:5173)

---

## 🙋‍♂️ Author

**Subhadeep Dutta**  
📧 [Email](mailto:subhadeepdutta12@gmail.com)  
🌐 [GitHub](https://github.com/subhadeepdutta12)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
