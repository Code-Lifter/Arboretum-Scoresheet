https://code-lifter.github.io/Arboretum-Scoresheet/


# Arboretum Smart Scorepad 🌲

A digital score calculator and companion app for the board game Arboretum.
"Lose the paper, save the trees."

## 🚀 Overview
The Arboretum Smart Scorepad is a lightweight, single-file web application designed to replace paper score sheets. It automates the complex scoring math required at the end of an Arboretum game, supporting 2, 3, or 4 players.
Unlike standard spreadsheet templates, this app features local storage persistence, ensuring your game data is never lost if the browser refreshes or your phone screen locks.

## ✨ Key Features
Smart Scoring: Automatically sums scores for all 10 species (Blue Spruce, Cassia, Cherry Blossom, Dogwood, Jacaranda, Maple, Oak, Royal Poinciana, Tulip Poplar, Willow).

Data Persistence: Uses the browser's localStorage to save names and scores instantly. Your game state survives tab closures and refreshes.

Dynamic Rule Adjustment: Automatically adjusts the number of visible tree species based on player count.

2 Players: 6 species

3 Players: 8 species

4 Players: 10 species

Instant Winner Detection: Highlights the leading player in real-time with a gold pulsing animation.

"Soft" Reset: Includes a custom modal allowing you to clear scores for a new round while keeping player names intact—perfect for consecutive games.

Mobile-First Design: Optimized for smartphones with large touch targets and no-zoom input fields.

## 🛠️ How to Use

Select Player Count: Use the dropdown at the top to switch between 2, 3, or 4 players.

Enter Names: Tap the "P1", "P2" headers to rename players.

Input Scores: Tap the grid cells to input points for each tree species. Navigation is optimized for mobile keypads.

View Results: The footer updates automatically. The winner is highlighted in gold.


## 🤖 For AI & Developers

This tool is built as a Single Page Application (SPA) contained entirely within one HTML file. It requires no backend server, no database, and no build process.

Tech Stack: HTML5, Vanilla JavaScript, Tailwind CSS (via CDN), FontAwesome.

State Management: Reactive state updates triggered by input events; state serialized to JSON in localStorage.

Accessibility: Semantic HTML tables with proper scope attributes for screen readers.


## 📄 License

This project is open-source. Feel free to modify and distribute.
