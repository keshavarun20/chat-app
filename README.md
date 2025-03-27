# Real-Time Chat Application

This project implements a real-time chat application using **WebSocket** and **STOMP** protocols. It allows users to send and receive messages in real-time, with a connection status indicator to show whether the WebSocket connection is active.

## Features

- Real-time messaging using WebSocket and STOMP.
- Simple user interface for sending and displaying messages, built with **Thymeleaf**.
- Connection status indicator (Green for connected, Red for disconnected).
- Lightweight chat application with **Bootstrap** styling.

## Technologies Used

- **Frontend**: HTML, JavaScript, Thymeleaf, Bootstrap
- **Backend**: Spring Boot (WebSocket, STOMP)
- **WebSocket**: SockJS
- **STOMP**: Protocol for message exchange over WebSocket


### Test the Application

- Open multiple tabs or browsers to simulate multiple users.
- Once connected, the status indicator will turn green.
- Send messages from one client and they should appear in real-time on other clients.

## Future Improvements

- Add authentication for users.
- Support for private messaging or group chats.
- Improve UI with advanced features like message timestamps and user status.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
