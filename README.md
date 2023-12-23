# SnakeGame-HTML-CSS-JS
Here's a breakdown of the Snake game implementation using HTML, CSS, and JavaScript:

1.HTML (index.html):
The HTML file contains the structure of the webpage.
It includes a game-container div that holds the game elements: the snake (snake div) and the food (food div).
External CSS and JavaScript files are linked to the HTML document.

2.CSS (style.css):
The CSS file defines the styles for the game elements.
The game-container is styled as a square with a border.
The snake (snake div) and food (food div) are styled as squares with different background colors.

3.JavaScript (script.js):
The JavaScript file handles the game logic and interactions.
The game starts when the DOM content is loaded (DOMContentLoaded event).
The snake is represented as an array of objects, where each object has x and y properties representing the position of a snake segment.

Game Logic:
The snake moves in the chosen direction (up, down, left, right) at regular intervals.
If the snake's head collides with the food, the snake grows, and a new food position is generated.
If the snake collides with the walls or itself, the game ends, and a message is displayed.
The game loop continues, providing a continuous gaming experience.

![image](https://github.com/rheashetty23/SnakeGame-HTML-CSS-JS/assets/108348171/81a8d2fa-a3c5-430b-bc07-ccc4aabaccf0)

