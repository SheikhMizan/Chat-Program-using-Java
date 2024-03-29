# Online Chat Application README

## Overview:

This Java application is a simple online chat system that enables multiple users to connect to a central server, send messages, and receive messages from other users in real-time. The application is implemented using socket programming for client-server communication.

## Server Implementation:

The server-side of the application is implemented in the `ChatServer` class. It creates a server socket to manage connections from multiple clients. The server assigns a unique user ID to each connected client and maintains a list of connected users. Messages received from clients are broadcasted to all connected clients.

## Client Implementation:

The client-side of the application is implemented in the `ChatClient` class. Each client connects to the server using sockets. Clients can send messages to the server, which are then broadcasted to all connected clients. Additionally, clients receive messages from other users in real-time.

## User Interface:

The user interface for the client is a simple text-based interface. Users can input messages through the console and view received messages in the console output. Screenshots of the text-based user interface are provided below.

## Running the Application:

To run the chat application, follow these steps:

1. Compile the Java files: `javac ChatServer.java ChatClient.java`
2. Start the server: `java ChatServer`
3. Start one or more clients: `java ChatClient`
