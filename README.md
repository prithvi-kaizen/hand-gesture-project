# hand-gesture-project

An interactive, real-time 3D particle system controlled by hand gestures. This project fuses WebGL creative coding with computer vision to create a "Minority Report" style interface where users can manipulate 3D shapes in mid-air.

## ✨ Features

*   **Real-time Hand Tracking:** Control the 3D scene using your webcam. No mouse or keyboard required.
*   **20,000+ Particles:** High-performance rendering using `BufferGeometry` for fluid 60FPS animations.
*   **Shape Morphing:** Smoothly transition between mathematical forms (Heart, Sphere, Flower, Saturn, Buddha, Fireworks).
*   **Smart Gestures:**
    *   **One Hand:** Tilt and Pan the object (Holographic effect).
    *   **Two Hands:** Zoom in/out (Distance) and Rotate (Steering wheel motion).
*   **Liquid Glass UI:** A modern, frosted-glass interface designed for macOS/High-DPI displays.
*   **Privacy First:** All video processing happens locally in your browser. No video is sent to any server.

## 🚀 Tech Stack

*   **Frontend:** HTML5, CSS3 (Glassmorphism)
*   **3D Engine:** [Three.js](https://threejs.org/) (WebGL)
*   **Computer Vision:** [Google MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
*   **Language:** Modern JavaScript (ES6 Modules)

## 📦 Installation & Usage

### Option 1: Quick Start (VS Code)
1.  Download the `index.html` file.
2.  Install the "Live Server" extension in VS Code.
3.  Right-click `index.html` and select **"Open with Live Server"**.

### Option 2: Python Simple Server
If you have Python installed, you can run a local server in the project folder:

```bash
# Python 3
python -m http.server 8000
