# Bouncing Balls 

This project is an interactive web-based simulation of bouncing balls using HTML5 Canvas and JavaScript. It creates a visually engaging animation of colorful balls bouncing around the screen with random trajectories, colliding with each other and the canvas boundaries.

## Features

- Multiple bouncing balls with random colors
- Random trajectory changes on collisions
- Ball-to-ball collision detection and response
- Boundary collision with visual effects and random angle changes
- Responsive canvas that adjusts to window size
- Customizable ball properties (number, speed, size)

## How It Works

The simulation uses HTML5 Canvas for rendering and JavaScript for the animation logic. Key components include:

- Ball creation with random properties
- Collision detection between balls and with canvas boundaries
- Randomized collision response, changing ball directions unpredictably
- Visual effects on collisions
- Continuous animation using `requestAnimationFrame`

## Customization

You can easily customize the simulation by adjusting the following parameters in the script:

- `numberOfBalls`: Total number of balls in the simulation
- `minSpeed` and `maxSpeed`: Range for ball velocities
- `sizeOption`: Set to 'same' for uniform ball sizes or 'different' for random sizes
- `uniformSize`: Size of balls when `sizeOption` is 'same'
- `minSize` and `maxSize`: Size range when `sizeOption` is 'different'

## Usage

1. Clone this repository or download the HTML file.
2. Open the HTML file in a modern web browser.
3. The simulation will start automatically.
4. Resize the browser window to see the responsive behavior.
