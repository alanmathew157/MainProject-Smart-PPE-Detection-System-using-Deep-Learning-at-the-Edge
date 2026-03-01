#  Smart PPE Detection System using Deep Learning at the Edge

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![YOLO](https://img.shields.io/badge/Object%20Detection-YOLO-red)
![Made with KiCad](https://img.shields.io/badge/Hardware-Raspberry%20Pi-green)

---

## 📌 Project Overview

This project presents a **Smart Personal Protective Equipment (PPE) Detection System** designed for industrial environments using **Deep Learning at the Edge**.

The system detects whether workers are wearing essential safety equipment such as:

- 🪖 Helmet  
- 🦺 Safety Vest  
- 🧤 Gloves  

It uses **YOLO-based object detection models** to perform real-time detection and generate alerts in case of non-compliance.

---

##  Objective

To enhance industrial safety by:

- Automating PPE compliance monitoring
- Reducing manual inspections
- Providing real-time alerts
- Improving workplace safety culture

---

## 🧠 Technologies Used

- Python
- YOLOv8, YOLOv7, YOLOv5
- OpenCV
- Raspberry Pi (Edge Deployment)
- ESP32
- Webcam Module
- 5V Buzzer

---

## ⚙️ System Architecture

1. Image Capture using Webcam  
2. Image Preprocessing  
3. YOLO Model Inference  
4. PPE Detection  
5. Alert Trigger (Buzzer / Notification)  
6. Real-time Monitoring Interface  

---

## 📊 Model Performance Comparison

| Model     | Dataset Size | Epochs | Accuracy |
|-----------|--------------|--------|----------|
| YOLOv8    | 240 Images   | 10     | 85.29%   |
| YOLOv7    | 1200 Images  | 54     | 89.45%   |
| YOLOv5    | 240 Images   | 100    | 60–70%   |

🔎 **Observation:** YOLOv7 achieved the highest accuracy, while YOLOv8 demonstrated strong performance with a smaller dataset.

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-username/PPE-Detection-System.git
cd PPE-Detection-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Detection

```bash
python detect.py
```

---

## 🔔 Alert Mechanism

When PPE non-compliance is detected:
- Buzzer is activated
- Alert is generated on interface
- Incident can be logged

---


## 🚀 Future Improvements

- Deploy fully on Raspberry Pi with optimization
- Add cloud dashboard monitoring
- Add IoT integration
- Improve dataset size for better accuracy
- Deploy using TensorRT for faster inference

---

## 📚 Academic Project

This project was developed as part of the B.Tech in Electronics & Communication Engineering (2024–2025).

---

## 👨‍💻 Author

**Alan Mathew**  
Electronics & Communication Engineering  
