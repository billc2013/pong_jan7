# Classic Pong Game

A simple implementation of the classic Pong game using vanilla HTML, CSS, and JavaScript. The game features a player-controlled paddle on the left side and an AI-controlled paddle on the right side.

## Features

- Smooth paddle and ball movement
- Simple AI opponent
- Score tracking
- Realistic ball physics with angle-based paddle deflection
- Speed increase on each paddle hit
- Game over state with restart functionality
- Responsive canvas sizing

## How to Play

1. Use the **Up** and **Down** arrow keys to move your paddle (left side)
2. The AI controls the right paddle
3. First player to score 5 points wins
4. Press **Space** to restart after a game ends

## Game Configuration

The game's behavior can be easily modified by adjusting the `CONFIG` object in the JavaScript code:

```javascript
const CONFIG = {
    canvas: {
        width: 800,
        height: 400
    },
    paddle: {
        width: 10,
        height: 60,
        speed: 5,
        margin: 50
    },
    ball: {
        size: 8,
        speed: 5,
        speedIncrease: 0.2
    },
    score: {
        winScore: 5
    }
};
```

## Installation

1. Clone this repository:
   ```bash
   git clone [your-repository-url]
   ```

2. Open `index.html` in your web browser

No additional dependencies or build steps are required!

## Code Structure

The game is built using an object-oriented approach with the following main classes:

- `GameObject`: Base class for game objects with position and dimension properties
- `Paddle`: Extends GameObject to handle paddle movement and constraints
- `Ball`: Extends GameObject to handle ball movement, collisions, and scoring

## Contributing

Feel free to fork this repository and make improvements. Some possible enhancements could include:

- Adding sound effects
- Implementing a two-player mode
- Adding power-ups
- Creating different AI difficulty levels
- Adding touch/mobile support

## License

This project is open source and available under the MIT License.