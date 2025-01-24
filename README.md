# Real-time Chat Application

A real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js) combined with Socket.io for seamless real-time messaging. The application features user authentication, online status indicators, image sharing, and a responsive, modern UI styled with TailwindCSS and Daisy UI.

## Features

- **Authentication & Authorization**: Secure user authentication and role-based access control implemented using JWT (JSON Web Tokens).
- **Real-time Messaging**: Instant messaging powered by Socket.io for efficient and reliable communication.
- **Online User Status**: Real-time updates for user presence and availability.
- **Image Upload & Storage**: Upload and store images using Cloudinary for efficient image management.
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
- **Cloudinary**: Cloud-based service for image upload, storage, and management.

## Installation

### Prerequisites

Ensure you have the following installed:

- Node.js (>= 14.x)
- MongoDB (local or cloud instance)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/barkinrl/chat-app
   cd chat-app
   ```

2. **Install dependencies**:

   ```bash
   npm run build
   ```

3. **Set up environment variables**:

   - Create a `.env` file in the root directory and add the following:
     ```env
     PORT=5001
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     ```

4. **Run the application**:

   ```bash
   npm run start
   ```

5. **Access the app**:
   Open your browser and navigate to `http://localhost:5001`.

## Project Structure

```
realtime-chat-app
├── backend          # Node.js backend
├── frontend         # React frontend
├── package.json     # Project configuration
└── README.md        # Project documentation
```

## Scripts

- `npm run build`: Install dependencies for both backend and frontend.
- `npm run start`: Start the backend and frontend on the same port.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [MERN Stack](https://www.mongodb.com/mern-stack)
- [Socket.io](https://socket.io/)
- [TailwindCSS](https://tailwindcss.com/)
- [Daisy UI](https://daisyui.com/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [Cloudinary](https://cloudinary.com/)

---

Happy coding!
