# WebSocket Chat Application

A real-time chat application built using React (Vite) for the frontend and Spring Boot for the backend. The application enables live communication between clients using the WebSocket protocol.

## Tech Stack

Frontend:

* React (Vite)

Backend:

* Spring Boot

WebSocket:

* STOMP
* SockJS

## Features

* Real-time messaging between users
* WebSocket-based communication
* Client-server architecture
* Simple and responsive user interface

## Project Structure

```
websocket-chat-app/
│
├── frontend/    # React (Vite) application
├── backend/     # Spring Boot application
```

## How to Run

### Backend (Spring Boot)

1. Open the backend project in Eclipse or IntelliJ
2. Run the main application class

The server will start at:

```
http://localhost:8080
```

### Frontend (React + Vite)

```
cd frontend
npm install
npm run dev
```

The frontend will run at:

```
http://localhost:5173
```

## WebSocket Endpoint

```
http://localhost:8080/ws
```

## Notes

* Ensure the backend is running before starting the frontend
* Make sure both frontend and backend ports match the configuration
* Do not send messages before the WebSocket connection is established

<img width="626" height="349" alt="image" src="https://github.com/user-attachments/assets/fcdf45e3-8e2e-4ce0-b272-afa485ea9f65" />

<img width="578" height="357" alt="image" src="https://github.com/user-attachments/assets/2102cf8a-370f-4d00-8ae5-e84acc7888b1" />

<img width="1894" height="941" alt="image" src="https://github.com/user-attachments/assets/f973273a-8146-45f4-89af-6fdc218d12d7" />

