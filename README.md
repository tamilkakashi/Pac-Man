Pacman Game README
Overview
This project is a simple web-based implementation of a Pacman-like game using HTML, CSS, and JavaScript. Players can add animated Pacman characters to a designated area and start a movement simulation where they bounce off the edges of the container.

Features
Add Pacman: Dynamically create Pacman characters at random positions within the container.
Start Game: Begin the animation where Pacman characters move around the container, bouncing off walls.
Animation: Pacman changes its image based on movement direction, simulating a more dynamic look.
Prerequisites
A modern web browser (Chrome, Firefox, etc.) to run the HTML file.
Images for the Pacman animations must be available in the ./images/ directory. Ensure you have the following images:
PacMan1.png
PacMan2.png
PacMan3.png
PacMan4.png
How to Use
Clone the Repository: Download or clone this repository to your local machine.
Images: Make sure to place the required Pacman images in the images folder.
Open the HTML File: Open index.html (or whatever you've named it) in a web browser.
Add Pacman: Click the "Add Pacman" button to create a new Pacman character.
Start Game: Click the "Start Game" button to begin the movement animation.
Code Structure
HTML: The basic structure is defined with a container for the game and buttons to control the game.
CSS: Styles are applied to the container to give it a background color and border.
JavaScript:
Pacman Creation: The create() function generates new Pacman characters at random positions.
Movement: The move_pac() function handles the animation and bouncing logic.
License
This project is open-source and available for personal or educational use. Feel free to modify and expand upon it!

Acknowledgments
Inspired by classic arcade games, this project serves as a fun way to explore web development concepts.
