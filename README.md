# Three.js Project Setup Comparison

This repository contains three different setups for working with Three.js, demonstrating different levels of complexity and toolchain usage.

## Project Structure

### 1. basic (Vanilla HTML + JS)

A simple setup using Three.js directly from a CDN without any build tools. This is useful for quick prototyping and understanding the core Three.js functionality.

Tech stack: HTML, JavaScript

**How to run**: 
Open index.html in a browser

### 2. vite (Vite + Three.js)

A more advanced setup using Vite for module bundling and including Three.js as a dependency. This setup also introduces OrbitControls for better interaction with the 3D scene.

Tech stack: Vite, Three.js

**How to run**:
```
cd vite
npm install
npm run dev
```

### 3. vite+react (Vite + React + React Three Fiber)

A React-based setup utilizing react-three/fiber for integrating Three.js into a React environment. This project includes a custom RotatingCube component, as well as Sparkles and OrbitControls from @react-three/drei.

Tech stack: Vite, React, React Three Fiber, Drei

**How to run**:

```
cd vite+react
npm install
npm run dev
```

## Features

- Basic: Simple Three.js setup with minimal dependencies.
- Vite: Fast development environment with module bundling.
- Vite + React: Component-based architecture with React and enhanced Three.js integration using react-three/fiber and @react-three/drei.

## Requirements

Ensure you have Node.js installed to run the Vite-based projects.