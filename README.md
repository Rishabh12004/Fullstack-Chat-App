# Chat App

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.IO for real-time communication.

## Features

- Real-time messaging with Socket.IO
- User authentication and authorization
- Persistent chat history using MongoDB
- Responsive design for mobile and desktop
- Group and private chat functionality

## Tech Stack

- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.IO

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Rishabh12004//Fullstack-Chat-App.git
    cd chat-app
    ```

2. Create a `.env` :
    ```
    MONGO_URI=your_mongodb_connection_string
    PORT=...  
    JWT_SECRET=your_jwt_secret
    NODE_ENV=...
    ```

4. Start the development servers:
    ```bash
    npm run build

    npm start
    ```

5. Open your browser and navigate to `http://localhost:5001`.

## Usage

1. Register or log in to your account.
2. Start a new chat or join an existing one.
3. Enjoy real-time messaging with other users.

## Folder Structure

```
chat-app/
├── frontend/       # React frontend
├── backend/       # Node.js backend
└── README.md     # Project documentation
```