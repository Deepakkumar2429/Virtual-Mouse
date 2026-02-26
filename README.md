# Virtual Mouse using OpenCV and Mediapipe
🚀 Project Overview
                 This project implements a Virtual Mouse system using OpenCV, Mediapipe, and PyAutoGUI. By tracking hand gestures and finger positions, this system allows users to control their computer's mouse without any physical hardware! It's a great demonstration of computer vision techniques applied to real-world use cases.

# Key Features:
- Tracks hand and finger movements using Mediapipe Hands.
- Allows smooth cursor movement.
- Supports left-click, double-click, and scroll functionalities based on hand gestures.
- Integrates PyAutoGUI to simulate mouse actions.
# Tech Stack:
- Python
- OpenCV for image processing.
- Mediapipe for hand landmark detection.
- PyAutoGUI for simulating mouse events.
# How It Works:
- Index finger moves the mouse cursor.
- Thumb and index finger pinch triggers a single-click.
- Index and middle finger pinch triggers a double-click.
- Open palm gestures trigger scroll actions.# 👁️🖱️Virtual Mouse System using Eye Gestures
🚀 Project Overview: 
                 This project implements a Virtual Mouse system using Eye Gestures powered by computer vision and facial landmark detection. By tracking eye movements and blink patterns through a webcam, users can control their computer’s mouse without any physical hardware. It demonstrates how real-time vision processing can enable hands-free human-computer interaction and improve accessibility.

# ✨Key Features:
- Eye movement tracking for cursor control
- Smooth and responsive cursor movement
- Single blink detection for left-click
- Double blink detection for double-click
- Eye direction–based scrolling
- Hands-free computer interaction

# 🛠️Tech Stack:
- Python
- OpenCV – Video capture and image processing
- MediaPipe – Facial landmark and eye tracking
- PyAutoGUI – Mouse control automation

# ⚙️How It Works:
### 👀 Cursor Movement
The system tracks eye landmarks using MediaPipe Face Mesh.  
The position of the iris/pupil is mapped to screen coordinates to move the cursor.
### 😉 Left Click
A deliberate blink (closing eyes for a short duration) triggers a left-click.
### 😉😉 Double Click
Two rapid blinks within a defined time threshold trigger a double-click event.
### ⬆️⬇️ Scrolling
Looking upward scrolls up.  
Looking downward scrolls down.

# 📂 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/virtual-eye-mouse.git
cd virtual-eye-mouse
```

### 2️⃣ Install Dependencies
```bash
pip install opencv-python mediapipe pyautogui
```

### 3️⃣ Run the Project
```bash
python main.py
```

---

# 💻 Requirements

- Python 3.7+
- Webcam
- Good lighting conditions for accurate eye detection
