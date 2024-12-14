# Bomberman Game

## Overview

This Bomberman game is a thrilling console-based action game built in C++ that supports both single-player and multiplayer modes. Players navigate a grid-based map, planting bombs to eliminate enemies and destroy obstacles while avoiding damage. The game features increasing difficulty levels, destructible obstacles, a boss level, and a leaderboard to track high scores.

---

## Features

### Gameplay Modes

- **Single Player**: Battle enemies and progress through levels, culminating in a challenging boss fight.
- **Multiplayer**: Engage in cooperative gameplay with another player to defeat enemies and survive.

### Core Mechanics

- **Bomb Planting**: Players plant bombs that detonate after a delay, dealing damage within a specific radius.
- **Enemy AI**: Enemies move randomly across the grid, adding unpredictability and challenge.
- **Health System**: Players and enemies have health points that decrease upon taking damage.
- **Boss Level**: Face off against a powerful boss with unique mechanics in the final level.

### Additional Features

- **Leaderboard**: Displays the top three high scores.
- **Dynamic Difficulty**: Levels feature varying layouts, obstacles, and enemy placements.
- **Power-ups**: Gain additional health, bombs, or other bonuses by meeting specific conditions.

---

## Controls

- **Arrow Keys**: Move Player 1 (Up, Down, Left, Right).
- **W, A, S, D**: Move Player 2 (in multiplayer mode).
- **Space**: Plant bomb for Player 1.
- **B**: Plant bomb for Player 2 (in multiplayer mode).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bomberman-game.git
   ```
2. Compile the code using a C++ compiler (e.g., g++, Visual Studio).
3. Run the executable file to start the game.

---

## How to Play

1. **Start the Game**: Run the program and choose a mode from the main menu:

   - Single Player
   - Multiplayer
   - Leaderboard
   - Exit

2. **Navigate the Grid**: Use the controls to move your player, avoiding enemies and obstacles.

3. **Plant Bombs**: Strategically place bombs to destroy enemies and clear paths.

4. **Survive and Progress**: Eliminate all enemies or defeat the boss to progress to the next level.

5. **Track Your Score**: Achieve the highest score and secure your spot on the leaderboard.

---

## File Structure

- `SourceCode.cpp`: The main source file containing the game logic.
- `leaderboardscore3.txt`: Stores the top three scores for the leaderboard.
- Audio files (`*.wav`): Used for sound effects.

---

## Requirements

- Windows operating system (due to use of `<windows.h>` and related features).
- C++ compiler (e.g., GCC, Visual Studio).
- Audio hardware for sound effects.

---

## Future Improvements

- Add additional power-ups and abilities.
- Implement advanced enemy AI.
- Introduce new levels and map designs.
- Create a graphical user interface (GUI).

---

## Credits

- Developed by Muhammad Zain

---

## License

This work is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. 

You may not:
- Use this code without crediting the original author (Muhammad Zain).
- Modify or redistribute this work without explicit written permission.

For disputes regarding ownership or misuse, contact mztahir006@gmailcom

## Copyright

Copyright (c) 2024 Muhammad Zain All rights reserved.

Unauthorized reproduction, redistribution, or claiming authorship of this work is strictly prohibited and subject to legal action. In the event of a dispute, authorship will be verified through commit history and repository timestamps.

