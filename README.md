# Real-Time Drowsiness Detection System

This repository contains the implementation of a **real-time drowsiness detection system** using **YOLOv5**. The system is designed to monitor drivers' drowsiness by detecting eye closure and yawning, providing timely alerts to prevent accidents.

## Features

- Real-time detection at **30 FPS** on GPU.
- Accurate detection of closed eyes and yawns with ~80% accuracy.
- Uses **YOLOv5** for robust feature detection.

## Dataset

- The model was trained and tested on a dataset containing annotated images of drivers exhibiting:
    - Normal behavior (awake and focused).
    - Drowsy behavior (eyes closed, yawning).
  Custom datasets can be added to further improve the model's accuracy.

## Results

- Performance Metrics:
    - Accuracy: ~90% for detecting drowsy behaviors.
    - Latency: Real-time processing at 30 FPS.
- Confusion Matrix:
    - True Positive (Drowsy Detected Correctly): 81%.
    - True Negative (Awake Detected Correctly): 75%.
    - False Positive (Awake Detected as Drowsy): 25%.
    - False Negative (Drowsy Detected as Awake): 19%.

## Challenges

- False positives in low-light conditions.
- Difficulty distinguishing between normal blinking and drowsy behavior.

