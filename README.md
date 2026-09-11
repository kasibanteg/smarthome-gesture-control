# SmartHome Gesture Control

An Android application that controls SmartHome devices using hand gestures. This project is part of **CSE 535: Mobile Computing** and consists of an Android app and a local Flask server for receiving gesture videos.

---

## 📖 Overview

The app allows users to:
- Select a gesture from a dropdown of 17 options (lights, fan, thermostat, digits 0–9).
- Watch an expert gesture video with replay functionality (at least 3 replays).
- Practice the gesture by recording themselves for up to 5 seconds using the front camera.
- Upload the practice video to a local Flask server.

This project is **Part 1** of the SmartHome Gesture Control assignment and sets up the foundation for gesture classification in Part 2.

---

## ✨ Features

### Screen 1 — Gesture Selection
- Dropdown with 17 gestures:
  - Turn On Lights, Turn Off Lights
  - Turn On Fan, Turn Off Fan
  - Increase Fan Speed, Decrease Fan Speed
  - Set Thermostat
  - Digits 0 – 9

### Screen 2 — Expert Gesture Video
- Shows an expert performing the selected gesture.
- **Replay** button (at least 3 replays).
- **PRACTICE** button → goes to the camera screen.

### Screen 3 — Practice Recording
- Front camera recording for at most **5 seconds**.
- Videos saved with the naming convention:
