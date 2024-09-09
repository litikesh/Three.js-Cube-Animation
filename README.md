# Three.js Cube Animation

This is a simple 3D animation project that displays a rotating cube using **three.js**. The project demonstrates basic concepts such as creating a scene, setting up a camera, adding objects and lights, and rendering the animation.

## Table of Contents

- [Installation](#installation)
- [Code Structure](#code-structure)
- [How to Run](#how-to-run)
- [Features](#features)
- [Credits](#credits)

## Installation

1. Clone or download this repository.
2. Install a local web server to serve the project files. You can use the **Live Server** extension in Visual Studio Code or any other HTTP server.

## Code Structure

The project consists of two main parts:

- **HTML File (`index.html`)**:
  This file sets up the basic HTML structure and imports the necessary modules from the CDN.

  - It uses the **importmap** to load the `three.js` library from a CDN.
  - It loads the `main.js` file as a module to run the animation.

- **JavaScript File (`main.js`)**:
  This file contains the logic for creating the scene and rendering the 3D cube. The main steps include:

  1. Creating a scene.
  2. Setting up a camera.
  3. Creating and adding a 3D cube object.
  4. Adding a light source.
  5. Setting up a renderer to visualize the scene.
  6. Animating the cube by rotating it along the x and y axes.

## How to Run

1. Open the project folder.
2. Serve the `index.html` file through a local web server (or simply use a tool like **Live Server** in VS Code).
3. Open the browser, and you will see a rotating cube with the color `#468585`.

## Features

- **Rotating Cube**: A 3D cube is created and rotated along the x and y axes.
- **Lighting**: Directional lighting is added to illuminate the cube.
- **Scene Background**: The background of the scene is set to a light gray color (`#f0f0f0`).
- **Camera Setup**: A perspective camera is used for a 3D view of the cube.

## Credits

- **Three.js**: This project uses the [three.js](https://threejs.org/) library for rendering 3D graphics.
