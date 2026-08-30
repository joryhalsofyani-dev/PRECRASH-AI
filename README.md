
# PRECRASH-AI 🚗🤖

## AI-Assisted Road Safety and Traffic Diagnostics

PRECRASH AI is a proactive road-safety system designed to detect and assess potential collision risks in real time.

The system combines Artificial Intelligence, computer vision, sensor fusion, trajectory prediction, Edge AI, and V2X communication to provide proactive collision warnings.

---

## 🎯 Project Overview

Traditional driver assistance systems are mainly reactive. PRECRASH AI follows a proactive approach by analyzing the surrounding environment and predicting potential risks before a collision occurs.

The system includes:

- Real-time object detection using YOLOv8
- Future risk prediction using CNN-LSTM
- RGB Camera and LiDAR sensor fusion
- Time-to-Collision (TTC) calculation
- Edge AI deployment on NVIDIA Jetson Orin Nano
- ROS 2-based system architecture
- TensorRT model optimization
- V2X communication

---

## 🧠 System Pipeline

```text
Camera + LiDAR + V2X
        ↓
Object Detection
        ↓
Sensor Fusion
        ↓
Trajectory Prediction
        ↓
Risk Assessment
        ↓
Safe / Warning / Critical
        ↓
Driver Warning
