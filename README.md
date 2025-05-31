# 🧠 Real-Time Face Tracking with OpenCV & PyAutoGUI

This project uses a webcam to detect faces in real-time using OpenCV and tracks their position. It leverages `haarcascade` classifiers for face and eye detection and optionally integrates mouse position tracking with `pyautogui`.

## 🔍 Features
- Real-time face detection with `cv2.CascadeClassifier`
- Frame flipping for mirror-like effect
- Eye detection included
- Mouse position tracking with `pyautogui` (for reaction or control)

## 🛠️ Technologies Used
- OpenCV (`cv2`)
- Haarcascade classifiers
- PyAutoGUI (for interacting with screen/mouse)

## 📦 Requirements

```bash
pip install opencv-python pyautogui
