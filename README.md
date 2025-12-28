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


color-flipper/
├── index.html Application layout and buttons
├── script.js JavaScript logic for color handling
└── README.md Project documentation
------------------------------------------------------------------------------------------------


⚙️ Functional Breakdown
1. DOM Selection <br>
const body = document.getElementsByTagName("body")[0];<br>(Used to dynamically update the page background color.<br>
2. Static Color Handler<br>
function setColor(name) {<br>
  body.style.backgroundColor = name;<br>
} <br>(Updates the background color based on user selection.)<br>
3. Random Color Generator<br>
function randomColor() {<br>
  const red = Math.round(Math.random() * 255);<br>
  const green = Math.round(Math.random() * 255);<br>
  const blue = Math.round(Math.random() * 255);<br>

  body.style.backgroundColor = `rgb(${red}, ${green}, ${blue})`;<br>
}<br> (Generates and applies a random RGB color.)



