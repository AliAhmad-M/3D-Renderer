# 3D Renderer

A simple wireframe 3D renderer built in C using SDL2. The project explores the fundamentals of 3D graphics by projecting 3D vertices onto a 2D screen and drawing the resulting edges as lines.

## Features

- **Wireframe Rendering:** Represents 3D objects as vertices and edges.
- **Perspective Projection:** Uses a field-of-view-based projection to convert 3D coordinates into 2D screen positions.
- **Camera System:** Supports camera movement and rotation using keyboard input.
- **Vector Mathematics:** Uses vector operations, dot products, cross products, and axis-angle rotation.
- **SDL2 Rendering:** Draws projected edges using SDL2's line-rendering functions.

## Technical Details

The renderer transforms world-space coordinates into camera space before projecting them onto the screen. It uses a perspective projection formula based on the distance between the camera and each point. The implementation also explores **weak perspective projection**, which approximates perspective by using a shared depth value for an entire object.
