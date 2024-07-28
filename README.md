# Chat Application

This project is a simple chat application implemented in Java. It allows users to create or join chat rooms, add users to chat rooms, send and receive messages, and display active users in a chat room. The project demonstrates the use of design patterns like Singleton, Observer, and Adapter.

## Features

1. **Create/Join Chat Room**: Users can create or join a chat room by entering a unique room ID.
2. **Add User**: Users can add other users to a chat room.
3. **Send Message**: Users can send messages within a chat room.
4. **Display Chat Messages**: Users can view all messages in a chat room.
5. **Display Active Users**: Users can view all active users in a chat room.
6. **Observer Pattern**: Notifies clients of new messages or user activities.
7. **Singleton Pattern**: Manages the state of the chat rooms.
8. **Adapter Pattern**: Allows the system to work with different types of client communication protocols (WebSocket, HTTP, etc.).

## Project Structure
src
|-- main
| |-- java
| |-- ChatRoom.java
| |-- ChatRoomManager.java
| |-- ConsoleObserver.java
| |-- HTTPCommunicationProtocol.java
| |-- Message.java
| |-- Observer.java
| |-- User.java
| |-- WebSocketCommunicationProtocol.java
| |-- Main.java
|-- test
|-- java

Example Commands:-
  Creating/Joining a Chat Room: Enter Chat Room ID: Room123
  Adding Users: Enter username to join the chat room: Alice
  Sending Messages: Enter sender username: Alice, Enter message: Hello, everyone!
  Display Chat Messages: Chat Messages: [Alice]: Hello, everyone!
  Display Active Users: Active Users: [Alice]
