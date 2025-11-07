# sdag

## FPS Game Tester

A first-person shooter game tester built with Three.js for testing movement mechanics and gameplay features.

### Features

- **WASD Movement**: Standard first-person movement controls
- **Jumping**: Press Space to jump
- **Dashing**: Press Shift to perform a quick dash (has cooldown)
- **Sliding**: Press Ctrl to slide (has cooldown)
- **Wall Jumping**: Jump while next to a wall in mid-air to push off
- **Entities with Health**: Player and enemy entities have health systems
- **3D Environment**: Practice area with platforms and walls

### How to Use

1. Open `fps-tester.html` in a modern web browser
2. Click on the screen to start and lock the mouse pointer
3. Use the controls to move around and test mechanics

### Controls

- **W/A/S/D** - Move forward/left/backward/right
- **Mouse** - Look around
- **Space** - Jump (or wall jump when near a wall in air)
- **Shift** - Dash (1 second cooldown)
- **Ctrl** - Slide (1.5 second cooldown)
- **ESC** - Release mouse pointer

### UI Information

The top-left corner displays:
- Current health
- Movement speed
- Player state (standing, moving, jumping, dashing, sliding, wall jumping, in air)
- Position coordinates

### Development Notes

This is a tester/prototype. The game mechanics are functional and ready for further development into a full game.