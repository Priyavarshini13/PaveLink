# PaveLink: RSSI-Based V2V Network for Real-Time Road Pothole Alerts

## Overview

PaveLink is an intelligent road safety system designed to detect potholes and provide real-time hazard alerts to nearby vehicles. The project combines AI-based pothole detection using YOLOv8 with a proposed RSSI-based Vehicle-to-Vehicle (V2V) communication framework for road hazard dissemination.

The system aims to reduce pothole-related accidents, vehicle damage, and improve driver awareness through early warning mechanisms.

---

## Problem Statement

Road potholes are a major cause of accidents, traffic disruptions, and vehicle damage. Drivers often detect potholes too late to react safely.

According to recent reports:

* 23,000+ pothole-related accidents were reported in India between 2020–2024.
* 9,438 deaths occurred due to pothole-related accidents.
* Pothole-related fatalities increased by 53% over the last five years.

There is a need for a real-time road hazard detection and alert system.

---

## Proposed Solution

PaveLink performs:

1. Real-time pothole detection using YOLOv8.
2. Hazard alert generation.
3. RSSI-based V2V communication simulation using MATLAB.
4. RoadWatch integration for road condition monitoring.

---

## Features

* Real-time pothole detection
* YOLOv8 object detection model
* Vehicle hazard alert generation
* RSSI-based V2V communication simulation
* Road safety enhancement
* Smart transportation support

---

## Project Structure

```text
PaveLink/
│
├── train.py
├── val.py
├── test.py
├── predict.py
├── requirements.txt
├── tested.mp4
├── workflow.png
├── architecture.png
└── README.md
```

---

## Technologies Used

### Programming Language

* Python

### Deep Learning Framework

* YOLOv8 (Ultralytics)

### Libraries

* OpenCV
* NumPy
* PyTorch
* Ultralytics

### Simulation

* MATLAB (V2V Communication Simulation)

---

## Model Weights

Due to GitHub and hackathon file-size limitations, the trained model weights are hosted separately.

Model Download Link:
y8best.pt
https://drive.google.com/file/d/1w5gO2Gqu-JsWD3LA_4hS7KmjKgLO2dgO/view?usp=drive_link

---

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run Prediction

```bash
python predict.py
```

---

## Expected Output

* Pothole detection on road images/videos
* Hazard identification
* Vehicle warning generation
* Road safety improvement

---

## Future Scope

* Real-time V2V communication implementation
* Fog alert system
* Stopped vehicle detection alerts
* Smart city integration
* Cloud-based road monitoring

---

## Team

National Road Safety Hackathon 2026

Project:
PaveLink – RSSI-Based V2V Network for Real-Time Road Pothole Alerts

Tagline:
Detect. Alert. Protect.
