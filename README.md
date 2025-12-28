# Color Flipper | JavaScript Mini Project

A lightweight Color Flipper web application developed using HTML5, CSS3, and Vanilla JavaScript.
This project demonstrates DOM manipulation, event handling, and dynamic styling in JavaScript.

---

## Project Overview

The Color Flipper allows users to dynamically change the webpage background color using predefined color buttons or a randomly generated RGB color.
It is designed as a beginner-friendly frontend project focusing on JavaScript fundamentals.

---

## Key Features

- Predefined color switching (Green, Blue, Red)
- Random RGB color generation
- Real-time background updates
- Clean and minimal user interface
- Zero external dependencies

---

## Tech Stack

Technology | Purpose  
HTML5 | Markup and structure  
CSS3 | Button styling and layout  
JavaScript (ES6) | Logic and DOM manipulation  

---

## Folder Structure


📂 Folder Structure
color-flipper/
│
├── index.html        # Application layout and buttons
├── script.js         # JavaScript logic for color handling
└── README.md         # Project documentation
------------------------------------------------------------------------------------------------


⚙️ Functional Breakdown
1. DOM Selection
const body = document.getElementsByTagName("body")[0];(Used to dynamically update the page background color.)
2. Static Color Handler
function setColor(name) {
  body.style.backgroundColor = name;
} (Updates the background color based on user selection.)
3. Random Color Generator
function randomColor() {
  const red = Math.round(Math.random() * 255);
  const green = Math.round(Math.random() * 255);
  const blue = Math.round(Math.random() * 255);

  body.style.backgroundColor = `rgb(${red}, ${green}, ${blue})`;
} (Generates and applies a random RGB color.)



