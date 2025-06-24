# Real-Time Chat Application

A modern, real-time chat application built with Node.js and Socket.IO that enables users to communicate across multiple chat rooms with a sleek, responsive interface.

## 📋 Description

This is a full-featured chat application that allows users to:

- Join with a custom username
- Create and manage multiple chat rooms
- Send and receive messages in real-time
- View message history when joining rooms
- See user join/leave notifications

The application features a modern dark theme UI built with Tailwind CSS and provides a seamless chatting experience across different rooms.

## 🛠️ Technologies Used

### Backend

- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **Socket.IO** - Real-time bidirectional event-based communication
- **HTTP** - Built-in Node.js module for server creation

### Frontend

- **HTML5** - Markup structure
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Client-side functionality
- **Tailwind CSS** - Utility-first CSS framework
- **Socket.IO Client** - Real-time communication

### Development Tools

- **ESLint** - Code linting and formatting
- **Prettier** - Code formatting
- **Jest** - Testing framework

## ⚡ Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/oleksandr-kovalchuk/node-chat.git
   cd node-chat
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   ```

4. **Open your browser and navigate to**
   ```
   http://localhost:3000
   ```

## 🎯 Key Features

### 💬 **Real-Time Messaging**

- Instant message delivery using WebSocket connections
- Live typing indicators and user presence
- Message timestamps with proper formatting

### 🏠 **Room Management**

- **Create Rooms**: Users can create new chat rooms instantly
- **Join Rooms**: Switch between different rooms seamlessly
- **Rename Rooms**: Modify room names (except default "General" room)
- **Delete Rooms**: Remove rooms when no longer needed
- **Message History**: New users see all previous messages when joining

### 👤 **User Experience**

- **Persistent Username**: Username stored in localStorage for convenience
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Dark Theme**: Modern, eye-friendly dark interface
- **System Notifications**: Join/leave notifications for better awareness

### 🔧 **Technical Features**

- **Modular Architecture**: Clean separation of concerns with dedicated modules
- **Error Handling**: Robust error handling for edge cases
- **Memory Management**: Efficient in-memory storage for development
- **Socket Management**: Proper cleanup of connections and rooms

## 📁 Project Structure

```
├── public/
│   ├── index.html          # Main HTML file
│   └── js/
│       ├── main.js         # Application entry point
│       ├── auth.js         # Authentication handling
│       ├── socket.js       # Socket.IO client setup
│       ├── ui.js           # UI event handlers
│       ├── rooms.js        # Room management
│       └── messages.js     # Message rendering
├── socket/
│   └── socketHandlers.js   # Socket.IO server handlers
├── models/
│   ├── roomManager.js      # Room data management
│   └── userManager.js      # User data management
├── index.js                # Server entry point
├── package.json            # Dependencies and scripts
└── README.md              # Project documentation
```

---

**Built with ❤️ using Node.js and Socket.IO**
