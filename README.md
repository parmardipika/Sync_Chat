# 🔄 Sync Chat – Real-Time Chat App

**Sync Chat** is a powerful, real-time messaging application built with the **MERN** stack and **Socket.IO**. It supports seamless conversations, real-time user status, and a clean, responsive interface for both desktop and mobile users.

---

## ✨ Features

- 🔥 **Live Chat Messaging** – Send and receive messages instantly via WebSocket.
- 🟢 **Active Users Display** – Shows real-time online/offline status.
- 📱 **Responsive UI** – Fully optimized for all screen sizes.
- 🎨 **Modern & Clean Design** – Minimalist interface focused on usability.
- 🔐 **JWT Authentication** – Secure login and registration.

---

## 🛠 Tech Stack

| Layer       | Tech Used                           |
|-------------|--------------------------------------|
| Frontend    | React (Vite), Tailwind CSS (or Bootstrap) |
| Backend     | Node.js, Express.js                  |
| Database    | MongoDB (Mongoose)                   |
| Real-time   | Socket.IO                            |
| Auth        | JSON Web Token (JWT)                 |
| Tools       | Vite, Postman, Nodemon               |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

git clone :  https://github.com/parmardipika/sync-chat.git <br>
cd sync-chat <br>

### 2. Install Dependencies

cd client && npm install <br>
cd ../server && npm install <br>
cd ../socket && npm install <br>

### 3. Configure Environment Variables
Create a .env file in the server folder: <br>

MONGODB_URI=<your_mongodb_connection_uri> <br>
PORT=5000 <br> 
JWT_SECRET=<your_secret_key> <br>
JWT_EXP=30d <br>

### 4. Run the App (Development Mode)
In 3 separate terminals or use a process manager: <br>

cd client && npm run dev <br>
cd server && npm start <br>
cd socket && npm start <br>

Then open your browser and go to:
#### http://localhost:5000



## 📁 Project Structure

```
sync-chat/
├── client/    # React frontend
├── server/    # Express backend with authentication
└── socket/    # Socket.IO real-time server
```

## 🔒 Security & Performance

### Uses JWT for stateless, secure authentication
### Prevents XSS via frontend sanitization
### Modular code for scalable feature addition
### Real-time status updates without refresh


## 📘 License
#### This project is licensed under the MIT License.

## 🤝 Contributions
This version is maintained individually. For any collaboration requests, feel free to open an issue or contact me.

***❤️ Made with love by Dipika Parmar***

