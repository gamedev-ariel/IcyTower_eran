# IcyTower_eran
# Icy Tower Core Game Project

## Overview
This project is a basic implementation of the core mechanics for an **Icy Tower-style game**. It includes the essential elements to create a working prototype that can be expanded into a full game. Here's what has been built so far:

## Features Implemented

### 1. **Background and First Scene**
- A background was set up for the first scene to give the game a visual structure.
- The scene includes boundaries to restrict player movement within the playable area.

### 2. **Player Character Setup**
- A player character with:
  - Movement mechanics (left and right).
  - Jumping controlled by gravity.
  - Prepared animations (animations are not yet fully implemented).

### 3. **Game Boundaries**
- Horizontal boundaries prevent the player from moving outside the playable area.
- Scripted logic ensures smooth interaction with the game borders.

### 4. **Player Movement Scripts**
- Horizontal movement reacts to player input.
- Jumping is implemented using physics-based force.

### 5. **Random Platform Generation**
- Platforms are generated randomly with consistent spacing.
- This creates a dynamic challenge for the player.

### 6. **Core Game Loop**
- The game is designed as a foundation for progressive levels.
- When the player reaches the top of the screen (the "roof"), they transition to a new scene.

### 7. **Next Scenes (Planned)**
- The next scenes introduce additional challenges:
  - **Second Scene:** No floor; if the player falls, the game ends.
  - **Progression:** The player continues through more scenes and stages with increasing difficulty.

## How to Use
1. Open the Unity project.
2. Play the first scene ("SampleScene") to test the game.
3. Observe the following:
   - The player moves left and right within the boundaries.
   - The player jumps and lands on randomly generated platforms.
   - Reaching the top transitions to the next scene.
   - Falling below the floor ends the game.
4. Modify or expand the game mechanics as needed for more advanced gameplay.

## Notes
- This is a **basic game project** meant to serve as a starting point for further development.
- Current progress focuses on the core gameplay mechanics without advanced visual or audio effects.
- Additional features like scoring, animations, or more complex level designs can be added in future iterations.

Enjoy building your own version of Icy Tower!

for WAB: Player Z = -1
for Windows: Player Z = -0.0006061955