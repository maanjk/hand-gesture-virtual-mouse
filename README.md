# AI Virtual Mouse (Hand-Gesture Controlled Cursor)

Control your mouse cursor using only your hand and a webcam.  
This project uses **OpenCV** and **MediaPipe Hands** to track your fingers in real time and map simple hand gestures to mouse actions.

> Tested on: Windows, Python 3.10, CPU-only

---

## ✨ Features

- 🖱 **Cursor movement** – move the mouse pointer with your index finger
- 👆 **Left click & double-click** – pinch **index + middle** fingers
- ✊ **Drag and drop** – make a **fist** to grab, open your hand to release
- ☝☝☝ **Scroll** – raise **3 fingers** (index, middle, ring) and move your hand up/down
- 📝 **On-screen help** – live “Mode” text and gesture instructions drawn on the webcam feed

The implementation is lightweight and runs fully on the CPU using your normal webcam.

---

## 🧰 Requirements

- **Python**: 3.10 (recommended)
- **OS**: Windows (tested)
- **Hardware**: Any basic webcam

### Python dependencies

Defined in `requirements.txt`:

```text
opencv-python
mediapipe
numpy
pyautogui
