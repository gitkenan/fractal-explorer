# Fractal Explorer

## Overview
Fractal Explorer is a web-based application that allows users to visualize and explore various types of fractals, including the Mandelbrot set, Burning Ship, and Julia sets. The application leverages JavaScript and HTML5 canvas for rendering, with optimizations for performance and responsiveness.

## Features
- **Multiple Fractal Types**: Choose from Mandelbrot, Burning Ship, and two Julia sets.
- **Progressive Rendering**: Quickly generates a low-resolution preview and progressively refines the image for better detail.
- **Smooth UI**: Offloads heavy computations to a Web Worker, ensuring a responsive user interface.
- **Interactive Zooming**: Zoom in and out using mouse wheel or clicks, with the ability to zoom at the mouse position.
- **Dynamic Resizing**: Automatically adjusts the canvas size when the browser window is resized.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, etc.) that supports HTML5 and JavaScript.

### Installation
1. Clone or download the repository.
2. Open `fractal_matrix.html` in your web browser.

### Usage
1. Select a fractal type from the dropdown menu.
2. Use the mouse wheel to zoom in or out, or click to zoom at the mouse position (Shift + click to zoom out).
3. Observe the progressive rendering as the fractal is computed.

## Code Structure
- **HTML**: The structure of the application, including the UI elements and canvas for rendering.
- **CSS**: Basic styling for the UI and canvas.
- **JavaScript**: The core logic for rendering fractals, handling user interactions, and managing the Web Worker.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Inspired by fractal mathematics and visualization techniques.
- Uses HTML5 Canvas API for rendering graphics.