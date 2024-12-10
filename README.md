# Chess Game

Welcome to the **Chess Game** project! This real-time multiplayer chess game allows two players to compete against each other while other users can join as spectators. The project leverages a range of modern web technologies to provide a seamless and interactive experience.

<h2>Live link 🌍📡 - [  https://multiplayer-chess-game-01n3.onrender.com/  ]</h2>

![image](https://github.com/user-attachments/assets/4909f25d-5aa7-485a-aaa6-b17284cba9fe)


### Player 1 -> Create Room
![Screenshot 2024-12-10 181551](https://github.com/user-attachments/assets/62ed187e-78ad-4027-82c8-f9e62b45975e)


### Player 2 -> Join Room
![Screenshot 2024-12-10 181753](https://github.com/user-attachments/assets/825552c3-d473-490a-b6a4-89fca060774d)

### Game Play
![Screenshot 2024-12-10 181921](https://github.com/user-attachments/assets/f581c418-8b64-49d6-99d4-d7c0b943cb1b)


### Chat 
![Screenshot 2024-12-10 182044](https://github.com/user-attachments/assets/1a052971-11a9-439d-abf3-387b5c817007)

### Spectators
![Screenshot 2024-12-10 182142](https://github.com/user-attachments/assets/5be12f25-701f-4c09-bcbe-07ac130ba2a4)


## Features

- **Real-time Gameplay**: Players can compete in real-time thanks to Socket.io.
- **Spectator Mode**: Users can join and watch ongoing games without participating.
- **Room Creation and Joining Feature**: Users can create a room where they can set up a chess match, and players can join an existing room by entering the room ID
- **Modern UI**: Utilizes TailwindCSS for a clean and responsive design.
- **Chess Mechanics**: Powered by Chess.js to handle game rules and move validation.
- **Server-side Logic**: Built with Node.js and Express to manage game states and player interactions.
- **Dynamic Templating**: EJS is used for rendering dynamic content on the front-end.

## Technologies Used

- **Socket.io**: Enables real-time, bidirectional communication between the server and clients.
- **Express**: A fast, unopinionated, minimalist web framework for Node.js.
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **EJS**: Embedded JavaScript templating.
- **Chess.js**: A JavaScript library for chess move generation, validation, and other utility functions.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yashk9293/multiplayer-chess-game.git
    cd multiplayer-chess-game
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

4. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```

## Usage

- **Playing the Game**: Two players can start a game by navigating to the game URL. Players can make moves in real-time, and the game state will update for both players.
- **Spectating**: Additional users can join the game URL to watch the ongoing game without interfering.
