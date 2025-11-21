# Three.js 3D Model Viewer

A simple 3D model viewer built with [Three.js](https://threejs.org/). This project demonstrates basic optimizations and interactive features for displaying a GLB model in a web page.

## Features

- **Spinning Animation:** The model auto-rotates for dynamic presentation.
- **Animated Model Load:** The model smoothly scales up from tiny to full size when loaded.
- **Mouse/Touch Interactions:** Click/tap and drag to rotate the model, with inertia for natural movement.
- **Shadows & Lighting:** Realistic lighting and soft shadow effects using Three.js shadow maps.
- **Responsive Design:** Canvas and layout adapt to any screen size.

## Usage

1. Place your GLB model (e.g., `file_name.glb`) in the project directory.
2. Open `index.html` in a browser.
3. Interact with the model using mouse or touch.

## Customization

- **Model:** Change the filename in the loader to use your own GLB model.
- **Lighting/Shadow:** Adjust light and shadow settings in the script for different effects.
- **UI:** Edit the HTML/CSS for your own branding and layout.

## Technologies

- [Three.js](https://threejs.org/) (via CDN importmap)
- Vanilla JavaScript (ES Modules)
- HTML5 & CSS3

## Project Structure

```
index.html      # Main application file
venture_test.glb # Example 3D model
shoe.glb    # Example 3D model
```
