# Gesture Forge

Gesture Forge is a browser-based 3D object manipulation game controlled entirely through hand gestures. It combines **MediaPipe Hands** for real-time hand landmark tracking with **Three.js** for interactive 3D rendering.

The application runs on the client side, tracks up to two hands through the webcam, and maps gestures such as pinch, open palm, and fist to movement, rotation, and scaling.

<img width="1843" height="885" alt="image" src="https://github.com/user-attachments/assets/981287d7-0913-406e-a086-fcf5366693cd" />


> [Live Demo](https://edujeetX.github.io/GestureForge/)

## Features

- Real-time webcam-based hand tracking
- Detection and tracking of up to two hands
- Gesture-controlled 3D object manipulation
- Smooth movement, rotation, and scaling
- Two-hand scaling and spinning
- Interactive Three.js scene with lighting and shadows
- Mirrored webcam preview with hand landmarks
- Responsive status and gesture overlay
- Client-side processing with no backend
- Single-page implementation in `index.html`
- Automatic deployment through GitHub Actions and GitHub Pages

## Gesture Controls

| Gesture | Action |
|---|---|
| Pinch | Move the 3D object by moving the pinched hand |
| Open palm | Rotate the object by moving the hand horizontally or vertically |
| Fist | Scale the object by moving the hand vertically |
| Two pinches | Scale and spin the object using the distance and angle between both hands |

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Three.js
- MediaPipe Hands
- WebRTC `getUserMedia()`
- GitHub Actions
- GitHub Pages

## Project Structure

```text
gesture-forge/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy-pages.yml
```

## License
MIT
