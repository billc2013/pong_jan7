# Canvas Pong Game

A classic Pong implementation using HTML5 Canvas with player vs AI gameplay.

## Features
- Real-time paddle movement
- AI opponent with predictive movement
- Score tracking
- Progressive difficulty (ball speeds up during play)
- Collision detection and physics
- Visual feedback (colored paddle borders)

## Technical Implementation

### Core Components
1. **Game State Management**
   - Ball physics and position
   - Paddle positions and scores
   - Game loop control

2. **Input System**
   - Arrow key handling for player movement
   - AI movement based on ball trajectory

3. **Rendering System**
   - Canvas-based rendering
   - 60 FPS game loop using requestAnimationFrame
   - Visual elements: paddles, ball, score, center line

### Game Mechanics
- Ball speed increases after each paddle hit
- AI difficulty controlled by paddle speed and reaction time
- Score increases when ball passes opponent's paddle
- Paddle collisions affect ball trajectory

## Controls
- ↑ Up Arrow: Move paddle up
- ↓ Down Arrow: Move paddle down

## Setup & Running
1. Include the HTML file in your project
2. Game starts automatically on page load
3. No external dependencies required

## Code Structure
- HTML: Canvas element and score display
- CSS: Basic styling and layout
- JavaScript: Game logic and rendering

## Performance Considerations
- Optimized collision detection
- Efficient canvas rendering
- Smooth animation handling

## Future Enhancements
- Multiple difficulty levels
- Two-player mode
- Power-ups and special effects
- Sound effects and music
- Mobile touch controls