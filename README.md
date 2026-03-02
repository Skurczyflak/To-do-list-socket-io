# English

## Real-Time To-Do List (Socket io)

A collaborative real-time To-Do List application where multiple users connected to the same server can add, edit, and remove tasks instantly.
This project demonstrates real-time synchronization using WebSockets.

## Main Features

- Add new tasks
- Edit existing tasks
- Remove tasks
- Real-time updates across all connected users
- Shared task state between clients

## How It Works

- Users connect to a shared Express server.
- Socket io establishes a WebSocket connection.
- When a user adds, edits, or removes a task:
  - The event is emitted to the server
  - The server broadcasts the update to all connected clients
- All users see changes instantly without refreshing the page.

## Built With

- HTML
- CSS
- JavaScript
- Node.js
- Express
- Socket io

## Project Purpose

This project was created to practice:

- Real-time application development
- WebSocket communication
- Server-client architecture
- Event-driven programming
- Managing shared application state

## Requirements

- Node.js (tested on v24.12.0)
- npm

## How to Run

```bash
npm install
npm run start
```
## Media
![To-do-list-app](<image.png>)