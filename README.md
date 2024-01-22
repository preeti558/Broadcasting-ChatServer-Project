# Broadcasting ChatServer Project

This Broadcasting ChatServer project is a Java-based application that implements a simple chat server allowing multiple clients to connect, chat, and receive broadcasts. The project incorporates socket programming for communication, multi-threading for handling multiple clients concurrently, and Swing and AWT for GUI design.

## Features

- **Server-Side:**
  - Socket programming using `ServerSocket` for accepting incoming connections.
  - Multi-threading with `MyThread` class to handle each client connection.
  - Broadcasting messages to all connected clients.
  - Dynamic updating of the online users list.

- **Client-Side:**
  - Socket programming using `Socket` for connecting to the server.
  - Swing and AWT for GUI design with a user-friendly interface.
  - Login, send messages, log out, and exit functionalities.
  - Continuous listening for incoming messages using a separate thread (`ClientThread`).
 
    # Images
    ![1](https://github.com/preeti558/Broadcasting-ChatServer-Project/assets/110534074/d7b6e01f-bb9f-44e2-bfa4-9717f01c71bb) ![2](https://github.com/preeti558/Broadcasting-ChatServer-Project/assets/110534074/8548f227-d406-46cc-a8fb-fbac835d5f65)
    ![3](https://github.com/preeti558/Broadcasting-ChatServer-Project/assets/110534074/43d5f860-f8d1-4d27-82d5-bb8a4b4f7444) ![4](https://github.com/preeti558/Broadcasting-ChatServer-Project/assets/110534074/95dbb114-b241-400e-b4c9-6eda395c897f)


## Prerequisites

- Java Development Kit (JDK) installed.
- Basic understanding of Java, sockets, and multi-threading.

## How to Run

1. **Compile the Server and Client Classes:**

   ```bash
   javac MyServer.java
   javac MyClient.java
1.**Run the Server:**
The server will start and wait for client connections.

**2.Run the Client:**
Enter your desired username when prompted, and start chatting.

**Project Structure**
MyServer.java: Main class for the chat server.
MyThread.java: Class for handling each client connection in a separate thread.
MyClient.java: Main class for the chat client.
ClientThread.java: Class for handling incoming messages from the server on the client side.
Additional Notes
The project is a basic example and may lack certain features and optimizations for a production environment.
Exception handling is minimal; consider enhancing it for robustness.
Feel free to extend and modify the code to suit your specific requirements.
License
This project is licensed under the MIT License.

**Acknowledgments**
Special thanks to the Java programming language, Swing, and AWT for providing the foundation for this Broadcasting ChatServer project.
