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
    git clone https://github.com/Rishabh12004/chat-app.git
    cd chat-app
    ```

2. Install dependencies for both client and server:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. Create a `.env` file in the `server` directory and add the following:
    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Start the development servers:
    ```bash
    # In the server directory
    npm run dev

    # In the client directory
    npm start
    ```

5. Open your browser and navigate to `http://localhost:5173`.

## Usage

1. Register or log in to your account.
2. Start a new chat or join an existing one.
3. Enjoy real-time messaging with other users.

## Folder Structure

```
chat-app/
├── client/       # React frontend
├── server/       # Node.js backend
└── README.md     # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.