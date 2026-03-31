# UAV-Object-Detection-Teknofest

🛸 UAV Object Detection & Tracking - Teknofest 2026
Status: 🚧 In Active Development (Work in Progress)

This repository contains the core algorithms and research for our participation in the Teknofest UAV competition. The goal is to develop a high-performance, real-time computer vision pipeline for autonomous aerial monitoring.

🎯 Project Tasks
Task 1: Object Detection & Tracking
Real-time detection and segmentation of vehicles, people, and aero vehicles in park lots.
Optimized for small object detection from high-altitude UAV camera feeds.

Task 2: Geometric & Telemetry Integration
Estimating and processing geometric information from video sequences to enhance situational awareness.

Task 3: Object Matching & Re-identification
Matching detected objects across different frames and perspectives.

🛠 Tech Stack
Frameworks: PyTorch

Vision: YOLOv11 (Custom trained), OpenCV

Algorithms: SAHI (Slicing Aided Hyper Inference) for small objects, ByteTrack for robust tracking.

Optimization: CUDA, FP16 Half-Precision.
