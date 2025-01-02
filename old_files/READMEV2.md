# Classic Pong Game with Bonus Block

A unique twist on the classic Pong game using vanilla HTML, CSS, and JavaScript. The game features a player-controlled paddle on the left side and an AI-controlled paddle on the right side, plus a special bonus block that can instantly win the game!

## Features

- Classic Pong gameplay mechanics
- Smooth paddle and ball movement
- Simple AI opponent
- Score tracking
- Realistic ball physics with angle-based paddle deflection
- Speed increase on each paddle hit
- Special bonus block that awards instant victory
- Game over state with restart functionality
- Responsive canvas sizing

## How to Play

1. Use the **Up** and **Down** arrow keys to move your paddle (left side)
2. The AI controls the right paddle
3. Regular scoring: First player to score 5 points wins
4. Bonus scoring: Hit the red block to instantly win with +10 points!
5. Press **Space** to restart after a game ends

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
    },
    block: {
        width: 30,
        height: 15,
        points: 10,
        color: '#FF0000'
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
- `Block`: Extends GameObject to handle the bonus block mechanics

## Special Feature: Bonus Block

The red bonus block appears in a random position on the field. If you manage to hit it:
- You instantly win the game
- You get 10 bonus points
- The game ends immediately

When you restart:
- The block reappears in a new random position
- All scores reset to 0
- Regular gameplay resumes

## Contributing

Feel free to fork this repository and make improvements. Some possible enhancements could include:

- Adding sound effects
- Implementing a two-player mode
- Adding multiple bonus blocks
- Creating different AI difficulty levels
- Adding touch/mobile support
- Creating power-ups that modify gameplay

## License

This project is open source and available under the MIT License.