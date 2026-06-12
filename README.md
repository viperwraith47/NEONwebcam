# NeonWebcam

NeonWebcam is a touchless, gesture-controlled digital canvas built with HTML5 and JavaScript. It allows users to draw, erase, and pan across a canvas using simple hand movements tracked via their webcam.

## Features

* **Gesture-Based Controls:**
    * **Draw:** Use one finger (index) extended.
    * **Move/Pan:** Use two fingers (index and middle) extended.
    * **Erase:** Perform a pinch gesture (thumb and index close together).
* **Customizable Brushes:** Adjust brush size and choose from a variety of colors.
* **Canvas Utilities:** Undo functionality, clear canvas, and save your masterpiece as a PNG.
* **Real-time HUD:** On-screen status indicator to show your current active tool.

## How to Run

This project runs directly in the browser and does not require a backend server.

1.  Clone this repository or download `index.html`.
2.  Open `index.html` in a modern web browser (Chromium-based browsers recommended).
3.  Grant camera access when prompted.
4.  Once the hand tracking model loads, you are ready to draw!

## Technical 

* **Canvas API:** Used for rendering the drawing layer and frame processing.
* **Webcam API:** Used to capture and process real-time video input.
* **JavaScript:** Lightweight implementation for state management and gesture logic.

## Usage Guide

| Gesture | Action |
| :--- | :--- |
| **1 Finger** | Draws on the canvas. |
| **2 Fingers** | Pans/Moves the existing drawing. |
| **Pinch** | Erases content where your hand is positioned. |

*Note: For the best experience, ensure you have good lighting and that your hand is clearly visible to the camera.*

## License

This project is open-source. Feel free to modify and adapt the code for your own creative projects. For a demo visit: https://viperwraith47.github.io/NEONwebcam/
