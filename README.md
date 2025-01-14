# Click the Circle Game

## Overview
Click the Circle is a simple browser-based game where the goal is to click on a circle that decreases in size with each click. The game lasts for 60 seconds, and your objective is to achieve the highest score possible by clicking the circle as many times as you can before the timer runs out.

## How to Play
1. Open the game in any modern web browser.
2. A red circle will appear at a random position on the screen.
3. Click on the circle to score points.
4. Each time you click the circle:
   - Your score increases by 1.
   - The circle's size decreases by 2 pixels (minimum size is 10px).
   - A new circle spawns at a random position.
5. The game ends after 60 seconds, and your final score will be displayed.

## Features
- Randomly positioned circle for each click.
- Circle size decreases progressively, adding a challenge.
- Real-time score and timer display.
- Simple and responsive interface.

## Requirements
- A modern web browser (e.g., Chrome, Firefox, Edge, Safari).
- No additional software or plugins are required.

## Installation
1. Download the HTML file containing the game code.
2. Open the file in a web browser by double-clicking it or dragging it into the browser window.

## Customization
You can modify the game by editing the code:
- **Circle Size**: Change the initial size or minimum size of the circle in the JavaScript section.
- **Game Duration**: Adjust the timer duration by changing the value of `timeLeft` in the JavaScript.
- **Circle Color**: Update the CSS `.circle` class to change the circle's color.

## Example Code Snippet
Here is an example of how the circle's size is reduced in the game:
```javascript
circleSize = Math.max(10, circleSize - 2); // Decrease size but not below 10px
```
