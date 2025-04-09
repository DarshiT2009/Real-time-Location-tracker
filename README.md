

#  Real-Time Location Tracker  
A real-time location tracking web app that enables users to **track and share live locations** using **WebSockets** and **Leaflet.js** for interactive map experiences. 🚀

---

## 🌟 Features

- 📡 **Live Location Tracking** – Real-time updates with zero lag.  
- ⚡ **WebSocket Integration** – Fast and efficient data transmission via `Socket.IO`.  
- 🗺️ **Google Maps / Leaflet.js** – Smooth and interactive map rendering.  
- 🔐 **User Authentication** – Secure login/logout functionality.  
- 👥 **Multi-User Support** – Share and track multiple users simultaneously.  
- 🚨 **Custom Alerts** – Get notified when someone enters/exits a defined zone.

---

## 🔧 Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)  
- [Node.js & npm](https://nodejs.org/)

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd <project-folder-name>
```

### 2️⃣ Initialize the Project
```bash
npm init -y
```

### 3️⃣ Install Required Dependencies
```bash
npm install express socket.io
```

### 4️⃣ Run the Server
```bash
nodemon app.js
```
> 💡 Use `nodemon` to auto-restart the server on changes.

---

## 🔌 WebSocket Overview

- Clients connect using `socket.io-client` for real-time updates.  
- Server listens and **broadcasts** user location data.  
- Enables seamless location syncing across all connected users.

```js
// Server Side Sample
io.on('connection', (socket) => {
  socket.on('sendLocation', (data) => {
    socket.broadcast.emit('receiveLocation', data);
  });
});
```

---

## 🎥 Demo & Preview



- 🎬 **Video Walkthrough**: [Watch on YouTube](https://youtu.be/D4_LMv_6oIM)

---

## 🤝 Contributing

We ❤️ contributions!  
Feel free to:
- Fork the repository
- Raise pull requests
- Suggest new features or report bugs via [Issues](https://github.com/DarshiT2009/Real-time-Location-tracker/issues)


---

## 📌 Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Leaflet.js  
- **Backend**: Node.js, Express.js, Socket.IO  
- **Database (optional)**: MongoDB / Firebase (for history or alerts)

---

## 🙌 Acknowledgements

- [Leaflet.js](https://leafletjs.com/)  
- [Socket.IO](https://socket.io/)  
- [Google Maps Platform](https://developers.google.com/maps)

---

## 🚀 Final Thoughts

> **"Built for explorers, by explorers — because great ideas deserve to move in real time."**

---

