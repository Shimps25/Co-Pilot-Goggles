# 👓 Co-Pilot: Smart Vision-Assistance Goggles for the Visually Impaired

**Co-Pilot** is a wearable smart goggle system that empowers visually impaired individuals to navigate their environment confidently and independently. It integrates computer vision, deep learning, and real-time audio guidance into a thoughtfully engineered and ergonomically designed headset.

---

## 💡 Overview

Co-Pilot is more than a software model—it's a fully realized **hardware-integrated product**. It is designed with **human-centric engineering**, ensuring compactness, comfort, and functionality. The 3D-printed wearable is lightweight and adaptable, accommodating internal electronics without bulk or discomfort. Real-time guidance is delivered through spatial audio, while caregivers can remotely monitor user safety via cloud-based tools.

---

## 🧠 Core Features

- 🔎 **Object Detection & Classification**: Identifies real-world objects with type, distance, and orientation.
- 🧭 **Angle & Depth Estimation**: Helps users understand their environment with spatial context.
- 🎧 **Real-Time Audio Feedback**: Non-intrusive speaker placement provides clear, voice-based directions.
- ☁️ **Remote Monitoring System**: Sends environment and user status data to caregivers via ThingSpeak IoT platform.
- 🖨️ **3D Printed, Ergonomically Designed Goggles**: A lightweight form factor, compact internal layout, and user-comfort-focused shell.

---

## 🧩 Design & Engineering

The Co-Pilot headset was engineered with a focus on **form and function**:

### 🔧 Structural Design

- **Compact Layout**: Internal electronics including the Raspberry Pi, sensors, and power supply were arranged in layered plates to maintain stability and balance.
- **Cushioned Contact Points**: Custom padding at pressure zones to ensure extended wearability.
- **Ventilation and Heat Dissipation**: Channeling and airflow slots to avoid overheating.
- **Speaker Housing**: Integrated into side arms for clear, localized audio instructions without blocking ambient sound.

### 🖨️ 3D Printing Process

- **Material**: Lightweight and durable PLA+ used for stability and ease of wearing.
- **Simulation-Backed Design**: Structural integrity validated through stress analysis using CAD simulation tools.
- **Modularity**: Each segment is detachable and serviceable for maintenance and upgrades.

---

## 🖼 Visual Showcase

| Front View | Top View | Side View |
|------------|----------|-----------|
| ![Front](![image](https://github.com/user-attachments/assets/fbff9a04-f8a1-4df6-a1c8-85d2d666c81f)) | ![Top](![image](https://github.com/user-attachments/assets/6be74598-f947-4fc1-b2d0-ee13fa08b51f)) | ![Side](![image](https://github.com/user-attachments/assets/f5a962c6-77f6-4927-bae1-561d25c765f1)) |


---

## ⚙️ Hardware Architecture

- **Processing Unit**: Raspberry Pi 4
- **Sensor Suite**: Radar sensor, DHT11 for humidity/temp, camera module
- **Audio**: Compact speakers embedded in headset arms
- **Power**: Rechargeable Li-ion battery
- **Connectivity**: ESP32 for data transmission to cloud

---

## 🔬 Software & Vision Pipeline

- **Model**: SSD (Single Shot Detector), optimized for mobile inference
- **Dataset**: COCO - Common Objects in Context
- **Framework**: Python, OpenCV, TensorFlow Lite
- **Data Visualization**: ThingSpeak cloud for sensor/status monitoring

---

## 📊 Results Summary

- SSD model chosen for its speed, accuracy, and compatibility with edge devices.
- Successfully deployed model on Raspberry Pi for real-time inference.
- Fully functional prototype tested for comfort, voice guidance, and remote data streaming.

---

## 🚀 How the System Works

1. Camera captures real-time environmental input.
2. Raspberry Pi processes the image using SSD-based computer vision.
3. Detected objects are classified with their type, distance, and angle.
4. Audio instructions guide the user accordingly.
5. Environmental and device data is transmitted to ThingSpeak for remote access.

---


