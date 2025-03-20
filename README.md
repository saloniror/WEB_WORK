# WEB_WORK
# Word Antakshari Game

## Overview

Word Antakshari is a web-based game where players take turns providing words that start with the last letter of the previous word. The game is powered by Node.js, Express, MongoDB, and a frontend JavaScript interface.

## Features

- Fetches an English words dictionary and stores it in MongoDB.
- Starts a game with a random word.
- Validates player input to ensure words exist in the dictionary and follow the rules.
- Generates a next word for the player to continue the game.
- Implements a scoring system based on word length and streak.
- Includes a leaderboard to track top players.
- Timer-based gameplay for added challenge.

## Technologies Used

- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- Axios (for fetching words dataset)
- HTML, CSS, JavaScript (Frontend)

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB running locally or in the cloud

### Steps to Run the Project

1. Clone the repository:
2. Install dependencies:
3. Start MongoDB server (if not already running):
4. Run the server:
5. Open your browser and go to:

## API Endpoints

### Start Game

- **Endpoint:** `GET /start`
- **Response:**

### Play Turn

- **Endpoint:** `POST /play`
- **Request Body:**
- **Response:**

### Get Leaderboard

- **Endpoint:** `GET /leaderboard`
- **Response:**

## Gameplay Instructions

1. Enter your name to start the game.
2. The game provides a random starting word.
3. Enter a word that starts with the last letter of the current word.
4. If valid, the game continues with the next word.
5. Each valid word increases your score.
6. If time runs out or an invalid word is entered, the game ends.



##

