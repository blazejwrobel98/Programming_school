
# HTTP Client and Server

## Description
The goal of this project is to create a simple HTTP client and server in the C language. This project aims to introduce the basics of network programming and the HTTP protocol.

## Project Assumptions
- The HTTP server should be able to handle simple HTTP requests and respond to them.
- The HTTP client should be able to send requests to the server and receive responses.
- The communication between the client and the server should follow the basic principles of the HTTP protocol.

## Functionality
1. **HTTP Server**: Implement a server that listens for connections and responds to simple HTTP requests.
2. **HTTP Client**: Create a client that can send HTTP requests to the server and interpret the responses.
3. **Request Handling**: The server should be able to handle basic requests, such as GET.
4. **Network Communication**: Implement network communication according to the HTTP protocol specification.

## Implementation Tips
- Use TCP sockets for network connections.
- Familiarize yourself with the HTTP protocol specification to properly handle requests and responses.
- Implement the server so that it can handle more than one request at a time (e.g., through multithreading).

## Educational Goal
This project allows for practical application of knowledge about network programming, the HTTP protocol, and handling network requests and responses in the C language.
