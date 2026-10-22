# Wish Machine
Assignment 3: An interactive experience

## About
This is a small interactive web experience designed for anyone who wants a quiet moment to write down a wish.

## Core interaction
1. The user types a wish into the input box.
2. The user clicks the "Send wish" button.
3. The wish floats upward like a glowing particle and fades away, while a gentle random message appears.
4. The user can click "Reset" at any time to clear everything and start over.

The interaction loop: **user input + click** → **program creates floating particle animation** → **visual + text feedback**.

## How to run
This is a pure front-end webpage with no external dependencies and no installation required.
1. Open `index.html` in this repository.
2. Download the file and double-click it to open in any modern browser (Chrome, Edge, Safari, Firefox).

## Error handling
The program checks for empty input: if the user clicks "Send wish" without typing anything, a message appears and no animation is created.

## Screenshot
![screenshot](screenshot.png)

## Known limitations
- The particle animation is simple; no sound effect.
- Very long wish text may overflow the display area.

## Credits
All code was written independently for this assignment. No external libraries, third-party assets, or course examples were used.
