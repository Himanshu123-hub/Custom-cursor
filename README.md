Custom Mouse Cursor

About the Project

This is a simple and interactive Custom Mouse Cursor project built using HTML, CSS, and JavaScript.

The project creates a custom cursor element that follows the user's mouse movement inside the main section of the webpage. It uses JavaScript mouse events to track the cursor's position and dynamically update its location.

Features

Custom mouse cursor.

Cursor follows mouse movement.

Smooth interactive experience (depending on CSS styling).

Dynamic cursor positioning.

Simple and clean implementation.

Technologies Used

HTML5

CSS3

JavaScript

How It Works

First, JavaScript selects the custom cursor element and the main section using querySelector().

The mousemove event detects mouse movement inside the main section.

The dets.x property gets the horizontal mouse position.

The dets.y property gets the vertical mouse position.

JavaScript updates the cursor's left and top CSS properties to follow the mouse.

JavaScript Concepts Used

DOM Manipulation

querySelector()

addEventListener()

Mouse Events (mousemove)

Event Object

CSS Style Manipulation

How to Run

Clone or download this repository.

Open the project folder in VS Code.

Open index.html in your browser.

Move your mouse inside the main section to see the custom cursor in action.
