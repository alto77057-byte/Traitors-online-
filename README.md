# Traitors Online — single server

One Node.js app serves both the website and real-time WebSocket multiplayer.

Features: 2–12 players, private room codes, secret roles, tasks, Traitor eliminations, win conditions, host reset.

There is deliberately **no emergency meeting or in-game discussion**; use your group chat.

Run locally:
1. Install Node.js 18+.
2. `npm install`
3. `npm start`
4. Open `http://localhost:8080` in two browsers.

Deploy the whole folder to a Node.js host that supports long-running WebSockets. The app uses the host's `PORT`.
