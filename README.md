# Smart Pen

A real-time **Computer Vision–based virtual drawing application** that allows users to draw on the screen using their **index finger**.

The project uses **MediaPipe Hands** to detect and track hand landmarks through a webcam. The movement of the index finger is converted into a digital pen, creating a touch-free drawing experience.

---

## Features

* Real-time webcam-based hand tracking
* Index finger tracking
* Touch-free virtual drawing
* Glowing golden digital ink
* Smooth finger movement
* Shift key controlled drawing
* Spacebar to clear the drawing
* Ramadan-inspired dark and golden interface
* Runs directly in a web browser

---

## How It Works

The application processes the webcam feed using **MediaPipe Hands**.

1. The webcam captures the user's hand.
2. MediaPipe detects the hand and its 21 landmarks.
3. The application identifies the index fingertip (landmark 8).
4. The fingertip coordinates are mapped onto the canvas.
5. When the **Shift key is held**, the fingertip movement is recorded as a drawing path.
6. The recorded points are rendered as a glowing golden line.

```text
Webcam
   |
   v
MediaPipe Hands
   |
   v
Hand Landmark Detection
   |
   v
Index Finger Tracking
   |
   v
Coordinate Mapping
   |
   v
HTML Canvas
   |
   v
Virtual Drawing
```

---

## Technologies Used

* HTML5
* CSS3
* JavaScript
* MediaPipe Hands
* Web Camera API
* HTML Canvas

---

## Controls

| Control             | Action               |
| ------------------- | -------------------- |
| Move Index Finger   | Move the virtual pen |
| Shift + Move Finger | Draw                 |
| Release Shift       | Stop drawing         |
| Space               | Clear the drawing    |

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/murtazaansari2504/ramadan-pen.git
```

### 2. Open the Project

```bash
cd ramadan-pen
```

### 3. Run the Application

Open `index.html` in a modern web browser.

Allow camera access when prompted.

---

## Project Structure

```text
ramadan-pen/
|
├── index.html
└── README.md
```

---

## Computer Vision Component

This project falls under **Computer Vision** because it processes real-time camera input and uses hand landmark detection to track the position and movement of the user's hand.

The project demonstrates:

* Hand detection
* Hand landmark detection
* Finger tracking
* Real-time coordinate extraction
* Image and video processing
* Human-Computer Interaction

---

## Future Improvements

* Pinch gesture for drawing without the keyboard
* Gesture-based eraser
* Multiple pen colors
* Adjustable pen size
* Gesture-based controls
* Save drawings as images
* Additional Ramadan-themed visual effects
* Support for multiple hand gestures

---

## Author

**Murtaza Ansari**

---

## Acknowledgement

This project uses **MediaPipe Hands** for real-time hand landmark detection.

If you find this project useful or int
