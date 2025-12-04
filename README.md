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
```
---

## 🚀 Installation
Clone the repo and set up a virtual environment.

## Bash
```text
# 1. Clone the repository
git clone https://github.com/maanjk/hand-gesture-virtual-mouse.git
cd hand-gesture-virtual-mouse

# 2. Create a virtual environment (Windows)
python -m venv venv

# 3. Activate the virtual environment (Windows)
venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt
```

## On macOS / Linux, activation would be:
```text
source venv/bin/activate
```

## ▶️ Usage
Bash
```text
python virtual_mouse.py
A window titled "AI Virtual Mouse" will open.
Press q (with the window focused) to quit.
```
