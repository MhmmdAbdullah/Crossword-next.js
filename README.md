# 🧩 Crossword Puzzle Game

A modern, full-stack web application that brings the classic crossword experience to the digital age. Built with high performance and smooth user experience in mind.

---

## 📖 Overview

This repository features a crossword puzzle game built with **Next.js** for the frontend and **Node.js** for the backend. It offers a seamless, interactive experience for users to solve word puzzles in real-time.

## 🚀 Key Features

* **Interactive UI:** A responsive and sleek crossword grid built with **Tailwind CSS**.
* **Real-time Validation:** Instantly check if your answers are correct through a dedicated **Node.js API**.
* **Dynamic Puzzle Generation:** Fetches puzzle data and clues dynamically from the centralized backend.
* **Smart State Management:** Efficiently handles user progress, focus transitions, and input history.
* **Performance Optimized:** Utilizing Next.js rendering capabilities for fast loading and SEO friendliness.

## 🛠 Tech Stack

### Frontend
* **Framework:** Next.js (React)
* **Styling:** Tailwind CSS
* **State Management:** React Hooks / Context API

### Backend
* **Environment:** Node.js
* **Framework:** Express.js
* **Data Handling:** JSON-based puzzle structures (REST API)

---

## 🏗 System Architecture

The project follows a decoupled **Client-Server architecture**:

1.  **Frontend (Client):** Responsible for the grid rendering logic, keyboard navigation, and managing the local game state.
2.  **Backend (Server):** Acts as the "source of truth." It validates user inputs against the answer key and serves the puzzle data.

---

## 🛠 Installation & Setup

Get the project up and running locally in just a few steps:

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/crossword-game.git](https://github.com/yourusername/crossword-game.git)
cd crossword-game
