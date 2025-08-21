# 📡 Java Multi-Client Chat Application

This project is a classic command-line based, client-server chat application built using Java Sockets. It features a multi-threaded server that can accept and manage connections from multiple clients simultaneously. When a client sends a message, the server broadcasts it to every other client connected to the chat room.

---

## ✨ Features

### Server (`ChatServer.java`)
* **Multi-Threaded:** Employs a new thread for each client connection, allowing it to handle multiple clients concurrently.
* **Centralized Broadcasting:** Receives a message from one client and relays it to all other connected clients.
* **Connection Management:** Dynamically maintains a list of connected clients, adding new ones and removing those who disconnect.
* **Listens on Port 5000:** The server is hardcoded to listen for client connections on port 5000.

### Client (`ChatClient.java`)
* **Concurrent Operations:** Uses a dedicated thread to listen for incoming messages from the server, allowing the user to send and receive messages simultaneously without blocking.
* **User Identification:** Prompts the user to enter a name, which is prefixed to their messages.
* **Simple UI:** Operates entirely within the command-line for sending and viewing messages.
* **Connects to Localhost:** The client is configured to connect to the server at `localhost:5000`.

---

## 🚀 How to Run

1.  **Compile the Code:**
    Open your terminal, navigate to the directory containing the files, and compile both `.java` files.
    ```bash
    javac ChatServer.java ChatClient.java
    ```

2.  **Start the Server:**
    In the same terminal, start the server. It will wait for clients to connect.
    ```bash
    java ChatServer
    ```

3.  **Start Clients:**
    Open a **new terminal window** for each chat client you want to run.
    ```bash
    java ChatClient
    ```
    Repeat this step in separate terminal windows to have multiple users in the chat room.

4.  **Chat:**
    Each client terminal will ask for a name. After entering a name, you can start typing messages. The messages will appear in the terminals of all other connected clients.

---

## 🖼️ Output

Here is an example of what the session would look like with a server and two clients running.

---

## 📬 Contact

Created by **Sayed Zabiulla** - feel free to reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sayed%20Zabiulla-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sayed-zabiulla-b5bb0536b/)
[![GitHub](https://img.shields.io/badge/GitHub-SayedZabiulla-grey?style=for-the-badge&logo=github)](https://github.com/SayedZabiulla)
[![Gmail](https://img.shields.io/badge/Gmail-sayedzabeulla@gmail.com-red?style=for-the-badge&logo=gmail)](mailto:sayedzabeulla@gmail.com)

---