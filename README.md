# Node.js Chat App

This is a real-time chat application built with Node.js, Express, Socket.IO, and MongoDB. Users can sign up, log in, send messages to other users, and view online users.

## Features

- **User Authentication**: Users can sign up with a username and password, and log in to access the chat functionality.
- **Real-Time Messaging**: Messages are sent and received in real-time using Socket.IO, allowing for instant communication between users.
- **User Presence**: The application displays a list of online users in real-time, providing visibility into who is currently active.
- **Secure Communication**: Messages are sent securely over WebSocket connections, and user authentication is handled with JWT tokens and hashed passwords.
- **Responsive Design**: The frontend is designed to be responsive and works well on both desktop and mobile devices.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/fahad0samara/node-Chat-App
   ```

2. Navigate to the project directory:

   ```bash
   cd node-Chat-App
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the project root and add the following environment variables:

   ```plaintext
   PORT=5000
   MONGODB_URL=<your MongoDB connection string>
   JWT_SECRET=<your JWT secret key>
   ```

5. Start the server:

   ```bash
   npm start
   ```

6. Open your web browser and visit `http://localhost:5000` to access the application.

## Usage

- Sign up for an account or log in if you already have one.
- Once logged in, you'll see a list of online users on the sidebar.
- Click on a user's name to start a conversation.
- Type your message in the input field at the bottom and press Enter to send.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request to the main repository's `develop` branch.

## License

This project is licensed under the [ISC License](LICENSE).


