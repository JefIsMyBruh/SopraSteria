# Sopra Steria – Catch the Dot

This project contains two Jupyter notebooks developed for the Sopra Steria "Catch the Dot" case. The task involves controlling a system that tracks the position of a user's index finger to catch a randomly generated dot on the screen.

---

## 🎯 Task Description

- A dot appears randomly on the screen.
- The user must catch the dot using their **index finger** only.
- The model tracks the fingertip position in real time.
- A **score** is shown for the respective player.
- A **toggle** feature enables or disables the fingertip-tracking overlay.
- A **quit** option allows graceful termination of the application.

---

## 📂 Contents

### `soprasteria_standard.ipynb`
- Implements the core functionality for a **single-player** version.
- Tracks the index finger position and detects collisions with the dot.
- Displays score and handles quit functionality.
- Provides basic fingertip visualization.

### `soprasteria_extended.ipynb`
- Extends the functionality to support **two players**.
- Separately tracks both players' index fingers and maintains individual scores.
- Enhances visualization and interaction logic.
- Preserves the toggle and quit features.

---

## ⚙️ Requirements

Ensure the following Python packages are installed:

- `opencv-python`
- `mediapipe`
- `numpy`
- `time`
- `random`
