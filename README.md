# Object and Gender Detection System Using TensorFlow Lite

This Raspberry Pi-based project uses a TensorFlow Lite object detection model along with a gender classification model. It integrates GPIO-controlled components like a buzzer and distance sensor, and provides audio feedback using `espeak`.

## 📌 Features

- Real-time object detection using TFLite
- Gender detection using a separate gender classification model
- Distance measurement with HC-SR04 sensor
- Buzzer alert if an object is within a threshold distance
- Audio feedback using `espeak`
- Multithreaded video capture

## 🧰 Technologies Used

- Python 3.7+
- OpenCV
- TensorFlow Lite Runtime
- NumPy
- RPi.GPIO
- espeak

## 🚀 Setup Instructions

### 1. Install Dependencies

```bash
pip
