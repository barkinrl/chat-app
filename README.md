# Real-time Chat Application

A real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js) combined with Socket.io for seamless real-time messaging. The application features user authentication, online status indicators, and a responsive, modern UI styled with TailwindCSS and Daisy UI.

## Features

- **Authentication & Authorization**: Secure user authentication and role-based access control implemented using JWT (JSON Web Tokens).
- **Real-time Messaging**: Instant messaging powered by Socket.io for efficient and reliable communication.
- **Online User Status**: Real-time updates for user presence and availability.
- **Global State Management**: Zustand is used to manage application state effectively.
- **Error Handling**: Robust error handling on both the server and client sides to ensure a smooth user experience.

## Tech Stack

### Frontend

- **React**: Component-based UI framework.
- **TailwindCSS**: Utility-first CSS framework for responsive designs.
- **Daisy UI**: Pre-built components for TailwindCSS.
- **Zustand**: Lightweight state management library.

### Backend

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for building APIs.
- **Socket.io**: Real-time bidirectional communication.
- **MongoDB**: NoSQL database for data storage.
- **JWT**: Secure token-based authentication.

## Installation

### Prerequisites

Ensure you have the following installed:

- Node.js (>= 14.x)
- MongoDB (cloud instance)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
   ```

2. **Install dependencies**:

   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Set up environment variables**:

   - Backend: Create a `.env` file in the `server` directory and add the following:
     ```env
     PORT=5001
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
   - Frontend: Create a `.env` file in the `client` directory and add the API base URL if necessary.

4. **Run the application**:

   - Start the backend:
     ```bash
     cd backend
     npm run dev
     ```
   - Start the frontend:
     ```bash
     cd frontend
     npm run dev
     ```

5. **Access the app**:
   Open your browser and navigate to `http://localhost:3000`.

## Project Structure

```
realtime-chat-app
├── frontend(client)          # React frontend
│   ├── src
│   └── public
├── backend(server)          # Node.js backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── middleware
└── README.md       # Project documentation
```

## Scripts

### Backend

- `npm start`: Start the server.
- `npm run dev`: Start the server in development mode with live reloading.

### Frontend

- `npm run dev`: Start the React development server.

## Acknowledgments

- [MERN Stack](https://www.mongodb.com/mern-stack)
- [Socket.io](https://socket.io/)
- [TailwindCSS](https://tailwindcss.com/)
- [Daisy UI](https://daisyui.com/)
- [Zustand](https://zustand-demo.pmnd.rs/)

---

Stay coding \m/
