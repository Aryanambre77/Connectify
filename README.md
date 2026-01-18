# Connectify 💬

**Connectify** is a real-time messaging platform developed with MongoDB, Express, React, Node.js, and Socket.IO, featuring JWT-based authentication, live one-to-one chat, and real-time notifications.

---

## 🚀 Features

- 🔐 Secure user authentication using JWT and bcrypt  
- 👤 User profile management  
- 💬 One-to-one real-time chat  
- 🟢 Live messaging powered by Socket.IO  
- 🔔 Instant notifications for new messages  
- 📱 Responsive user interface  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Axios  
- CSS / Tailwind CSS  

### Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  

### Real-Time Communication
- Socket.IO  

### Authentication & Security
- JSON Web Token (JWT)  
- bcrypt  

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js  
- MongoDB (local or Atlas)  

### Clone the repository
```bash
git clone https://github.com/Aryanambre77/Connectify.git
cd Connectify

# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

```

---

### Environment Variables

Create a .env file in the backend directory and add:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

### ▶️ Run the Application

```bash
# Start backend
cd backend
npm start

# Start frontend
cd ../frontend
npm start
```

The app will run on:

Frontend: http://localhost:3000

Backend: http://localhost:5000

---

### 📌 Future Enhancements

Group chat functionality

Typing indicators

Read receipts

Media/file sharing

Deployment with Docker

---

📄 License

This project is for educational and portfolio purposes.
