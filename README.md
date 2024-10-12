# single pack man Animation Program

## Overview

The Pac-Man Animation program is a simple web application that allows users to create a Pac-Man character that moves back and forth across the screen. The character changes its appearance as it moves, simulating the classic Pac-Man game experience.

## Features

- **Dynamic Character Creation**: A Pac-Man image is created and appended to the document when the user clicks the "Start" button.
- **Back-and-Forth Movement**: The Pac-Man character moves from left to right and back again, changing its appearance based on the direction.
- **Smooth Animation**: The movement is smooth, with a delay between each position update.

## Technologies Used

- HTML
- JavaScript

## How to Use

1. **Open the HTML File**: Save the code to a `.html` file (e.g., `pacman_animation.html`) and open it in a web browser.
2. **Start the Animation**: Click the "Start" button to create the Pac-Man character and initiate its movement across the screen.

## Code Explanation

- **Image Array**: The `pacmen` array contains the filenames of the Pac-Man images used for different states.
- **Creating the Character**: The `create()` function creates an `<img>` element for Pac-Man and sets its initial properties (size, position, and source image).
- **Movement Logic**:
  - The `move()` function controls the character's movement. It checks the current position and direction:
    - Moves forward until it reaches a specified boundary (600 pixels).
    - Reverses direction and moves back to the starting position (0 pixels).
  - The character changes its image based on its current direction using the `front` variable to alternate between images.
- **Animation Timing**: `setTimeout(move, 200)` creates a delay between position updates, giving a smooth animation effect.

## Customization

You can customize the following aspects of the program:

- **Pac-Man Images**: Replace the image filenames in the `pacmen` array with your own Pac-Man images.
- **Movement Velocity**: Change the value of the `velocity` variable to adjust the speed of the Pac-Man's movement.
- **Movement Limits**: Modify the position limits (0 and 600) to change how far Pac-Man can move across the screen.

## Conclusion

This Pac-Man Animation program is a fun introduction to JavaScript animations and event handling. Feel free to experiment with the code and make it your own! Enjoy the journey with Pac-Man!
