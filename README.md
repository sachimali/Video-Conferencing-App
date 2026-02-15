# Video Conferencing Application

A full-stack video conferencing web application built with React and Node.js, featuring real-time video/audio communication, screen sharing, and user authentication.


## 🌟 Features

- **Real-time Video & Audio Communication**: High-quality peer-to-peer video calls
- **Screen Sharing**: Share your screen with other participants
- **User Authentication**: Secure signup and login system
- **Meeting History**: Track your past meetings
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Chat Functionality**: In-meeting text chat (in development)

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI framework
- **Material-UI** - Component library
- **WebRTC** - Real-time communication
- **Socket.io Client** - Real-time bidirectional communication

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Socket.io** - WebSocket implementation
- **JWT** - Authentication

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v14.x or higher)
- **npm** or **yarn**
- **MongoDB** account (or local MongoDB installation)
- **Git**

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the backend directory:

```env
PORT=8000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

Start the backend server:

```bash
npm start
```

The backend will run on `http://localhost:8000`

### 3. Frontend Setup

Open a new terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the frontend directory:

```env
REACT_APP_BACKEND_URL=http://localhost:8000
```

Start the frontend application:

```bash
npm start
```

The frontend will run on `http://localhost:3000`

## 🎯 Usage

1. **Sign Up**: Create a new account with your email and password
2. **Login**: Access your account using your credentials
3. **Start a Meeting**: Create a new video conference room
4. **Join a Meeting**: Enter a meeting code to join an existing room
5. **Share Screen**: Click the screen share button to share your display
6. **View History**: Check your past meetings in the history section

## 📁 Project Structure

```
.
├── backend/
│   ├── src/
│   │   ├── app.js           # Main application file
│   │   ├── controllers/     # Request handlers
│   │   ├── models/          # Database models
│   │   ├── routes/          # API routes
│   │   └── middleware/      # Custom middleware
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/      # Reusable components
│   │   ├── pages/           # Page components
│   │   │   ├── VideoMeet.jsx
│   │   │   ├── authentication.jsx
│   │   │   └── history.jsx
│   │   ├── utils/           # Utility functions
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── .env
│
└── README.md
```


## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Sachi Mali

⭐ **Star this repository if you find it helpful!**