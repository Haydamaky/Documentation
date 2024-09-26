# Monopoly Game

This project is a web-based **Monopoly game** built using **NestJS** for the backend, **Next.js** for the frontend, and **WebSockets** to enable real-time multiplayer interactions.

## Project Overview

The goal of this project is to create a fully-functional online Monopoly game where multiple players can connect, play in real-time, and interact with the game board and each other. Players will be able to roll dice, move their pieces, buy and sell properties, collect rent, and perform all the actions that are part of the classic Monopoly board game.

## Tech Stack

- **Frontend**: Next.js (React-based framework)
  - The game board, player interactions, and UI will be handled by Next.js.
  - The game will include components such as the Monopoly board, player tokens, property details, and game controls (roll dice, buy property, etc.).

- **Backend**: NestJS (Node.js framework)
  - The server-side logic, including game state management, player turns, property ownership, and rules, will be implemented using NestJS.
  - WebSocket-based communication between players and the server will handle real-time updates for all players.

- **Real-Time Communication**: WebSockets
  - WebSockets will enable real-time communication between the server and all connected clients, ensuring that all players can see live updates (e.g., dice rolls, moves, property purchases, etc.).
  - We'll use either **Socket.IO** or the **NestJS WebSocket module** to manage connections and broadcasts.

## Features (Planned)

- **Real-time Multiplayer**: Multiple players can join a game session and play simultaneously.
- **Turn-Based Logic**: Each player will take turns, and only the active player can roll the dice or perform actions on their turn.
- **Dice Rolling**: Players can roll virtual dice to determine their movement on the board.
- **Property Management**: Players can buy, sell, or trade properties, and collect rent from other players who land on their properties.
- **Game Board Rendering**: The Monopoly board will be displayed visually, and players' tokens will move in real-time based on dice rolls.
- **Chat Feature** (optional): Players will be able to chat with each other during the game.
- **Reconnect Feature**: Players who disconnect will be able to reconnect to the game, picking up where they left off.
- **Bankruptcy and Game Over Conditions**: Handling player bankruptcies and determining the game winner when all other players are eliminated.
