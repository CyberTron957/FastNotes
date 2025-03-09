# FastNotes - Simple Note-Taking App

Fast is a minimalist, web-based note-taking application with user authentication and automatic saving features. Built with Node.js, Express, and SQLite, it provides a clean, full-screen writing experience similar to traditional desktop notepads.
<img width="1405" alt="Screenshot 2025-03-09 at 3 29 56 PM" src="https://github.com/user-attachments/assets/4e213e3c-acfe-46d1-9a68-dc7e9e704ded" />

## Features

- **User Authentication**: Register and login with username/password
- **Full-Screen Writing**: Distraction-free interface that maximizes writing space
- **Auto-Save**: Automatically saves notes 1 second after typing stops
- **Local Storage**: Uses SQLite for persistent storage without external dependencies
- **Status Indicator**: Shows when you're typing and when notes are saved
- **Note Management**: Create new notes or continue editing the last note

## Tech Stack

- **Backend**: Node.js, Express
- **Database**: SQLite (local storage)
- **Authentication**: JWT (JSON Web Tokens), bcrypt for password hashing
- **Frontend**: Vanilla HTML/CSS/JavaScript

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/CyberTron957/FastNotes/
cd notepad-app
```
2. Install dependencies:

```bash

npm install
```
3. Run the application:

```bash

node app.js
```
Open your browser and visit: http://localhost:3000

