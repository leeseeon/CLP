# Real-Time Human Height Estimation System

## Overview

This project implements a real-time human height estimation system using computer vision and depth sensing.

It combines YOLOv8 object detection with Intel RealSense depth data to accurately estimate a person’s height in real time.

This system can be applied to smart environments, automation systems, and monitoring solutions.

---

## Key Features

* Real-time human detection using YOLOv8
* Accurate height estimation using RealSense depth data
* Live video processing with low latency
* Head-to-foot measurement using 3D coordinates
* Scalable and modular system design

---

## Tech Stack

* Python
* YOLOv8 (Ultralytics)
* Intel RealSense SDK
* OpenCV
* NumPy

---

## How It Works

1. Detect a person using YOLOv8
2. Extract head and foot key regions
3. Retrieve depth values from RealSense
4. Convert to 3D coordinates
5. Calculate real-world height

---

## System Architecture

Camera → YOLO Detection → Depth Extraction → Height Calculation → Output

---

## Demo

### 🔹 Real-Time Detection

<img width="1585" height="1263" alt="image" src="https://github.com/user-attachments/assets/2bd806d8-6bc7-4a8e-8afa-6960436188fd" />

### 🔹 Height Estimation Output

<img width="675" height="505" alt="image" src="https://github.com/user-attachments/assets/246fba01-34ce-44c3-aa39-08fc1bd71b1c" />

---

## Results

* Real-time performance with stable detection
* Reliable height estimation using depth data
* Works in indoor environments with consistent accuracy

---

## Why This Project Matters

This project demonstrates the integration of computer vision and depth sensing into a practical real-time system.

It is not just a prototype, but a working solution that can be extended into real-world applications such as:

* Smart surveillance systems
* Automated measurement systems
* AI-based monitoring solutions

---

## Future Work

* Multi-person tracking
* Web dashboard integration (React + WebSocket)
* Improved calibration for higher accuracy

---

## Author

Seeon Lee
