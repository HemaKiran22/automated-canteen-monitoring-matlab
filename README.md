# 🍽️ Automated Canteen Monitoring System (MATLAB Version)

This project implements a real-time queue monitoring system for a canteen using MATLAB and YOLOv8 object detection. It detects students in the queue, estimates the waiting time based on queue length, logs the information, and alerts if the queue gets too long. The system can operate using either a video file or a live webcam feed.

---

## 📌 Features

- 🧠 Uses **YOLOv8** for detecting people in real-time.
- 📹 Supports **video input** or **live webcam feed**.
- 🔲 Displays bounding boxes around detected students.
- ⏱️ Calculates **estimated wait time** based on queue length.
- 📈 Real-time **queue trend visualization**.
- 📁 Logs queue data with timestamps to `queue_log.txt`.
- 🔔 **Sound alert** when queue exceeds 10 people.

---

## 🛠 Requirements

- MATLAB with:
  - **Computer Vision Toolbox**
  - YOLOv8 support via `yolov8ObjectDetector`
- A compatible **webcam** (for live mode)
- Optional: `canteen2.mp4` video file for demo/testing

---

## 🚀 How to Run

1. Clone this repository or download the code.
2. Make sure the YOLOv8 model (`yolov8s`) is available.
3. Place your test video (optional) in the same directory and name it `canteen2.mp4`.
4. Open MATLAB and run:


