A simple browser-based video calling app built using WebRTC, Socket.io, and Express.js. It allows two users to join with a username, see who is online, and start a real-time video call with one click.

🚀 Features

1-to-1 real-time video calling

WebRTC peer-to-peer streaming

Socket.io signaling (offer, answer, ICE candidates)

Live user list / contacts panel

Simple and clean UI

End-call support with connection cleanup

🧰 Tech Stack

Frontend: HTML, CSS, JavaScript, WebRTC

Backend: Node.js, Express.js

Signaling: Socket.io



Open the app in your browser:

http://localhost:9000

📝 How It Works

Users enter a username to appear online

The server tracks connected users

Clicking a user creates a WebRTC offer

The receiver sends an answer

ICE candidates help establish the best route

Video streams directly between browsers (P2P)



 To-Do / Future Improvements

Add chat messaging

Add screen sharing

Add typing/online indicators

Improve UI animations
