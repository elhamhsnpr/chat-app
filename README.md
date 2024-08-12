# Chat App

This is a real-time chat application built with Node.js, Express, and Socket.io. The app allows users to communicate in real-time using websockets, with messages being instantly broadcasted to all connected clients.

## Features

- Real-time communication between users.
- Utilizes websockets for fast and efficient message delivery.
- User-friendly interface with Mustache.js templates.
- Timestamped messages using Moment.js.
- Query string parsing using QS.js.

## Technologies Used

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express**: Web framework for Node.js.
- **Socket.io**: Library for real-time web applications.

### Frontend

- **Mustache.js**: Logic-less template syntax for rendering messages.
- **Moment.js**: Library for parsing, validating, manipulating, and formatting dates.
- **QS.js**: A query string parsing and stringifying library.
- **Socket.io-client**: Client-side library for connecting to the Socket.io server.

## Installation

1. Clone the repository:

    ```bash
    git clone git@github.com:elhamhsnpr/chat-app.git
    cd chat-app
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the server in development mode with automatic restarts:

    ```bash
    npm run dev
    ```

    Or, run the server in production mode:

    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000` to view the chat app.

## Usage

- Users can join the chat room by entering a username and a room name.
- Once inside the chat room, users can send and receive messages in real-time.
- The chat interface will display messages from all users, including the sender's name and the time the message was sent.

## Dependencies

### Production

- `express`: ^4.19.2
- `socket.io`: ^4.7.5

### Development

- `nodemon`: ^3.1.4

## Frontend Libraries

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/mustache.js/3.0.1/mustache.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.22.2/moment.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/qs/6.6.0/qs.min.js"></script>
<script src="/socket.io/socket.io.js"></script>
