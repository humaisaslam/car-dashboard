---

# 🚗 Vehicle detection weights for yolov8

<div align="center">

**Real-time vehicle detection, tracking, and license plate recognition system weights**

**[🎥 Watch Project Demo](https://www.linkedin.com/posts/humaisaslam_computervision-yolo-ocr-activity-7412950854636429312-N5Il?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD__vkwBgYamfymTtJyXKbhzFJkSFqPsNfM)**

</div>

## 📋 Overview

This repository provides the core components for a sophisticated vehicle monitoring system. By combining **YOLOv11** for high-speed detection, **SORT (Simple Online and Realtime Tracking)** for vehicle continuity, and **OCR** for license plate authentication, this system offers a complete end-to-end computer vision solution.

---

## 🎯 Key Features

* **Advanced Detection:** Utilizes **YOLOv11** weights trained on 10 specific vehicle classes.
* **Persistent Tracking:** Implements the **SORT** algorithm to maintain unique IDs for vehicles across frames.
* **License Plate Recognition:** Integrated **OCR** for automated vehicle authentication.
* **Web-Based Interface:** A Flask-powered dashboard for real-time monitoring and data visualization.

---

## 📁 Project Structure

```text
car-dashboard/
├── model/                # YOLOv11 detection logic and trained weights
├── sort/                 # SORT algorithm implementation for object tracking
├── app.py                # Flask application for the web dashboard
├── utils/                # OCR and video processing utilities
└── README.md             # Project documentation

```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/humaisaslam/Pakistani-vehicles-yolo.git
cd Pakstani-vehicles-yolo

```

### 2. Install Requirements

```bash
pip install -r requirements.txt

```

### 3. Run the Demo

```bash
python app.py

```

---

<div align="center">

### ⭐ **Star this repo if you found it useful!**

**Developed by Humais Aslam Under Olive Digital PVT Ltd**)

</div>





