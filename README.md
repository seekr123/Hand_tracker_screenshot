# Hand_tracker_screenshot
Real-time hand gesture recognition app that captures screenshots using your webcam and MediaPipe.

This project detects hand landmarks via webcam, identifies gestures like “thumbs up,” and automatically saves a screenshot after a 5-second countdown. Designed to demonstrate gesture-based control using Python and computer vision libraries.

---

Features
- Real-time hand tracking using MediaPipe
- Recognizes gestures like "Thumbs Up", "Fist", "Peace", etc.
- Automatically saves a screenshot when a "Thumbs Up" is held consistently
- Countdown timer before screenshot
- Cooldown system to prevent accidental repeats
- Easily extendable to support new gestures or actions

---

Tech Stack
- Python 3.12
- OpenCV
- MediaPipe
- Threading

---

Getting Started

Clone the Repository
```bash
git clone https://github.com/yourusername/gesture-screenshot.git
cd gesture-screenshot
