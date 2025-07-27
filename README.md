# ✋ Virtual Hand Gesture Controller (Scroll with Hand Gestures)

This Python application uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to control scrolling on your computer using hand gestures detected via webcam.

### 📹 Description

This script:
- Uses your webcam to detect your hand in real time.
- Tracks your **index finger**.
- Automatically scrolls **Page Up** or **Page Down** depending on the horizontal position of your index finger.

This can be useful for:
- Touchless control in presentations
- Accessibility purposes
- Experimenting with gesture recognition

---

## 🛠️ Requirements

- Python 3.7+
- OpenCV
- MediaPipe
- PyAutoGUI

Install the dependencies using pip:

```bash
pip install opencv-python mediapipe pyautogui
