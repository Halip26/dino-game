# Dino Run Game 🦖

A Python recreation of the famous Chrome dinosaur game using **Pygame**.

## Description

This is a fun, arcade-style game where you control a dinosaur character that must jump over cacti and avoid flying birds to achieve the highest score possible. The game features increasing difficulty as you progress, with the game speed increasing every few seconds.

## Features

- 🎮 **Smooth Gameplay**: Real-time rendering at 60 FPS
- 🦖 **Animated Dino**: Walking, jumping, and ducking animations
- 🌵 **Dynamic Obstacles**: Randomly spawning cacti and flying birds
- ☁️ **Parallax Clouds**: Moving clouds in the background
- 🔊 **Sound Effects**: Jump, collision, and checkpoint sounds
- 📊 **Score Tracking**: Current score and high score display
- ⚡ **Increasing Difficulty**: Game speed increases as your score grows

## Controls

| Key                      | Action                          |
| ------------------------ | ------------------------------- |
| **SPACE** / **UP ARROW** | Jump                            |
| **DOWN ARROW**           | Duck                            |
| **RETURN** / **SPACE**   | Restart Game (Game Over Screen) |
| **ESC**                  | Exit Game (Game Over Screen)    |

## Installation

### Requirements

- Python 3.7+
- Pygame 2.0+

### Setup

1. Clone or download this repository
2. Navigate to the project directory
3. Install required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Game

```bash
python main.py
```

The game will start with an introduction screen where you can jump to begin!

## Game Mechanics

- **Score**: Increases automatically as you survive (1 point every ~7 frames)
- **Checkpoints**: Every 100 points, you'll hear a checkpoint sound 🔔
- **Speed**: The game gradually speeds up as you progress
- **Collision**: Colliding with obstacles ends the game, save your high score!

## Project Structure

```
dino-game/
├── main.py              # Main game file
├── README.md            # This file
├── requirements.txt     # Python dependencies
└── resources/           # Game assets (sprites, sounds)
    ├── dino.png         # Dinosaur sprite sheet
    ├── dino_ducking.png # Ducking animation
    ├── cactus-small.png # Cactus obstacles
    ├── birds.png        # Flying bird sprite
    ├── cloud.png        # Background clouds
    ├── ground.png       # Ground sprite
    ├── logo.png         # Game logo
    ├── game_over.png    # Game over text
    ├── replay_button.png # Restart button
    ├── numbers.png      # Score digits
    ├── jump.wav         # Jump sound
    ├── die.wav          # Collision sound
    └── checkPoint.wav   # Checkpoint sound
```

## How to Play

1. **Start Screen**: Press SPACE or UP to make the dino jump
2. **Gameplay**:
   - Jump over cacti by pressing SPACE or UP ARROW
   - Duck under flying birds by pressing DOWN ARROW
   - Avoid obstacles for as long as possible
   - Your score increases automatically
3. **Game Over**: Press RETURN or SPACE to restart, or ESC to exit

## Tips for Higher Scores

- 🎯 Time your jumps carefully to avoid obstacles
- 📈 Duck under birds instead of jumping to save time
- ⚡ Stay calm as the game speeds up - smaller movements often help
- 🏆 Try to reach checkpoints (multiples of 100) for encouragement

## Dependencies

See [requirements.txt](requirements.txt) for the full list of dependencies.

## Author

Created by [Halip26](https://github.com/Halip26)

## License

This project is open source and available for educational purposes.

## Disclaimer

This is an educational project inspired by the Chrome dinosaur game (by Sebastien Gabriel, Chrome UX team). It's created for learning purposes and is not affiliated with Google or Chrome.

---

Enjoy the game and try to beat your high score! 🦖🎮

Enjoy the game and try to beat your high score! 🦖🎮
