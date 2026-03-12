# 🎮 NexusGames

**NexusGames** is a pure front-end, serverless Peer-to-Peer (P2P) multiplayer gaming hub. Play classic games instantly with your friends over WebRTC—no backend, no databases, no sign-ups, and zero server lag!

🔗 **[Play Live Now: NexusGames](https://megatooluniverse.github.io/NexusGames/)**

---

## ✨ Enterprise-Grade Features

- **Zero-Backend Architecture:** Powered entirely by **WebRTC** and **PeerJS** for direct browser-to-browser data channels.
- **Deep Linking / Auto-Join:** Generate viral invite links that auto-fill the room code for seamless entry.
- **Live Ping/Latency Meter:** Real-time network telemetry tracking connection health (ms) between peers.
- **In-Game Chat & Emojis:** Full-duplex live chat with typing indicators and floating emoji reactions.
- **Glassmorphism UI:** Modern, responsive design with dynamic animated background orbs and smooth transitions.
- **Persistent Local Stats:** Uses `localStorage` to save your lifetime win records across sessions.
- **Hardware-Accelerated Confetti:** Custom HTML5 Canvas physics engine for victory celebrations.
- **Synthesized Audio:** Built-in web `AudioContext` generation for clicks, wins, and errors (No external heavy mp3 files).

---

## 🕹️ Included Games

1. **Tic Tac Toe ❌⭕** - The classic grid battle.
2. **Rock Paper Scissors 🪨📄✂️** - Blind-choice simultaneous action.
3. **Memory Card Match 🧠** - Host-shuffled, network-synced deck flipping.
4. **Number Guess Battle 🔢** - Closest-to-target logic with encrypted state locking.
5. **Speed Quiz Battle ⏱️** - Reflex-based trivia where the first correct answer steals the point.

---

## 🏗️ Under the Hood (How it works)

Unlike traditional multiplayer games that rely on heavy Node.js/Python servers to sync state, NexusGames uses a **Decentralized P2P Model**:
1. **The Matchmaker:** The PeerJS signaling server is used *only once* at the start to exchange connection tokens (the 6-digit code).
2. **The Handshake:** Once connected, the server steps out of the way.
3. **The Data Channel:** All game logic, state syncs, arrays, and chat messages travel *directly* between Player 1's device and Player 2's device in milliseconds.

---

## 🚀 How to Play

1. **Host a Game:** Go to the [live link](https://megatooluniverse.github.io/NexusGames/) and click **Create New Room**.
2. **Share the Link:** Copy the auto-generated invite link or code and send it to a friend via WhatsApp.
3. **Connect:** The guest clicks the link (or enters the code manually) to establish the WebRTC node.
4. **Play:** The Host starts the game engine, and the battle begins!

---

## 🛠️ Tech Stack

- **HTML5** (Canvas, Web Audio API)
- **CSS3** (Variables, Keyframes, Backdrop-filters)
- **Vanilla JavaScript** (ES6+, WebRTC)
- **PeerJS** (For simplified WebRTC signaling)

---

*Built with ❤️ for lag-free, instant gaming.*
