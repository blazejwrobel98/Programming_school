
# Network Chat

## Description
The aim of this project is to create a simple network chat in the C language, enabling text communication between two or more users over a network. This chat is a straightforward example of network-based user-program interaction.

## Project Assumptions
- Implementation of a client and server that communicate with each other using network sockets.
- Users can send and receive messages in real-time.
- Ability to handle multiple users simultaneously.

## Functionality
1. **Chat Server**: Launch a server that listens for connections from clients.
2. **Chat Client**: Implement a client that connects to the server and allows sending and receiving messages.
3. **Network Communication**: Use TCP/UDP sockets for transmitting messages between the client and the server.
4. **User Interface**: A simple text-based interface for the client to send and receive messages.

## Implementation Tips
- Use socket library for network connections.
- Implement multithreading on the server to handle multiple clients.
- Apply appropriate network protocols (TCP or UDP) based on the application's requirements.

## Educational Goal
This project aims for practical application of knowledge about network programming, threading, and user interaction with a program operating in a network environment.
