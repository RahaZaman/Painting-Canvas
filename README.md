# Assignment 1 - Painting Canvas (CSE 160: Intro to Computer Graphics)

## WebGL Drawing Application 🎨🖱️

## Overview

This project is a browser-based interactive drawing application built with WebGL and JavaScript. It allows users to draw geometric shapes (points, triangles, circles) on a canvas with customizable properties such as color, size, and brush type. This app is part of a CSE:160 graphics course assignment and includes both basic drawing features and creative enhancements beyond the core requirements.

---

## 🌟 Features

### ✅ Basic Features
- **Canvas-Based Drawing:** Users can click or drag the mouse across a canvas to draw shapes at selected locations.
- **Shape Types:** Supports drawing points, triangles, and circles.
- **Brush Selection Buttons:** Users can choose between point, triangle, and circle brushes.
- **Shape Size Control:** A slider allows adjustment of shape/brush size.
- **Color Customization:** Three RGB sliders dynamically control the color of shapes.
- **Clear Canvas:** A button clears all shapes from the canvas.
- **Segment Control for Circles:** A slider adjusts the number of segments used to render circles (for smoothness).
- **Mouse Drag Drawing:** Users can draw continuously by dragging while holding the mouse.
- **Code Organization:** Modular structure with functions like `setupWebGL()`, `connectVariablesToGLSL()`, `renderAllShapes()`, and `handleClick()`.
- **Object-Oriented Shapes:** Uses classes (`Point`, `Triangle`, `Circle`) for rendering each shape with encapsulated logic.

---

### Controls
- 🖱️ **Click** to draw a shape.
- 🖱️ **Click & Drag** to paint across the canvas.
- 🟦 **Buttons** to choose between Point, Triangle, and Circle tools.
- 🎚️ **Sliders** to adjust:
  - Red, Green, and Blue color values
  - Shape Size
  - Circle segment count
- 🧹 **Clear** button removes all drawn shapes.
- 🖼️ **Draw Art** recreates the hand-drawn triangle artwork.