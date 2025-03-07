# Real-Time Location Tracker

## Overview
A real-time location finder application that allows users to track and share their live location with others using WebSockets and Leaflet JS.

## Features
- **Live Location Tracking**: Get real-time location updates.
- **WebSocket Integration**: Fast and efficient data transmission.
- **Google Maps Integration**: Display locations interactively.
- **User Authentication**: Secure access with login/logout features.
- **Multi-User Support**: Share locations with multiple users simultaneously.
- **Custom Alerts**: Notify users when someone enters/exits a specific area.

## Prerequisites
Make sure you have the following installed:
- **Git**: [Download & Install Git](https://git-scm.com/)
- **Node.js**: [Download & Install Node.js](https://nodejs.org/)
- **npm**: Comes with Node.js installation

## Setup Instructions

### Step 1: Clone the Repository
```sh
git clone <repository-url>
cd <project-folder-name>
```

### Step 2: Initialize the Project
```sh
npm init -y
```
This will create a `package.json` file with default configurations.

### Step 3: Install Dependencies
```sh
npm install
npm install express socket.io
```
This installs all required packages, including Express and Socket.io for real-time communication.

### Step 4: Run the Server
```sh
nodemon app.js
```
This will start the server with **Nodemon**, ensuring automatic restarts on file changes.

## WebSocket Implementation
- Clients connect via WebSockets for real-time updates.
- Server broadcasts location updates to all connected users.

## Contributing
Pull requests are welcome! Open an issue to suggest improvements.


🚀 Happy Coding!

