# Pong Variants

A collection of Pong games implemented using HTML5 Canvas, featuring both classic and breakout versions.

## Game Versions

### Classic Pong
- Traditional player vs AI gameplay
- Progressive difficulty with increasing ball speed
- Real-time paddle movement and collision physics
- Score tracking system

### Breakout Pong
- Combines classic Pong with Breakout mechanics
- Destructible blocks for additional scoring
- Expert mode for enhanced difficulty
- Toggle between game modes during play

## Controls
- ↑↓ Arrow keys: Move paddle
- B: Toggle breakout mode (Breakout version only)
- X: Toggle expert mode (Breakout version only)

## Implementation Details

### Class Diagrams
Located in `diagrams/` directory:
- `classic-class.mmd`: Classic Pong class structure
- `breakout-class.mmd`: Breakout Pong class structure
- `classic-flow.mmd`: Classic Pong game flow
- `breakout-flow.mmd`: Breakout Pong game flow

### Technical Stack
- HTML5 Canvas for rendering
- Pure JavaScript implementation
- Mermaid.js for technical diagrams

## Setup
1. Open `index.html` in a browser
2. Select desired game version
3. Use keyboard controls to play

## Project Structure
├── index.html
├── classic.html
├── breakout.html
├── diagrams/
│   ├── classic-class.mmd
│   ├── breakout-class.mmd
│   ├── classic-flow.mmd
│   └── breakout-flow.mmd
└── README.md
