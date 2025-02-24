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

# Online Monopoly Game - MVP Completed 🎉  

The **MVP** of the Monopoly game project has been successfully implemented! All planned core features are functional, though some bugs remain, and we're actively working on fixing them.

## 🔹 How to Play  
To enjoy the Monopoly experience, gather a **group of four registered players** (each with a verified email). Follow these simple steps to start playing:  

1. **Go to the Main Page** and click the **"Play"** button.  
2. **Create a Game Room** or join an existing one.  
3. Once all four players are connected, you’ll be **automatically redirected** to the **/game** page.  
4. Enjoy playing Monopoly in real time!  

## ✅ Features (Implemented)  

- **Real-time Multiplayer**: Players can join and play together simultaneously.  
- **Turn-Based Logic**: Only the active player can roll the dice and take actions.  
- **Dice Rolling**: Virtual dice determine movement.  
- **Property Management**: Buying, selling, trading, and rent collection are fully functional.  
- **Game Board Rendering**: A visual board with real-time player movement.  
- **Chat Feature**: Players can communicate during the game.  
- **Reconnect Feature**: Players can rejoin if they disconnect.  
- **Bankruptcy & Game Over Conditions**: Players are eliminated when bankrupt, and the last one standing wins.  

## 🛠 Current Work  
- **Bug Fixing**: Addressing various bugs to improve stability.  
- **Refactoring**: Enhancing code quality using best practices like **SOLID principles**.
- **Optimization for All Devices**: Ensuring smooth gameplay across **desktop, tablet, and mobile**.   

## 🚀 Future Plans  
- **Friends System & Profiles**: Adding player profiles with custom avatars and friend lists, making it more social.  
- **In-Game Marketplace**: Introducing a market for custom game items (e.g., unique dice, board fields).  

Exciting updates are on the way! Stay tuned.  

