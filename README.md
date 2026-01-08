# 🚗 Driven Unwanted Pose Detection System

This is a real-time computer vision system that detects unsafe or unwanted driver postures—such as drowsiness, distraction, or sleeping—using pose estimation and deep learning. Built with Python, OpenCV, and TensorFlow, this project aims to enhance road safety by alerting drivers before accidents occur.

---

## 📌 Features

- 🔍 Real-time webcam-based driver monitoring
- 🧠 Pose estimation using key body landmarks
- 😴 Drowsiness and distraction detection
- 🚨 Alert system for unsafe behaviors
- 📊 Modular and extensible architecture

---

## 🛠️ Tech Stack

| Component        | Technology         |
|------------------|--------------------|
| Language         | Python 3.x         |
| Computer Vision  | OpenCV             |
| Deep Learning    | TensorFlow         |
| Pose Estimation  | MediaPipe / OpenPose (optional) |
| Alert System     | Audio              |

---

## 📂 Project Structure

```
DrivenPoseDetection/
├── dataset/                # Training data (images/videos)
├── models/                 # Trained models
├── utils/                  # Helper scripts (e.g., alert triggers, preprocessing)
├── main.py                 # Entry point for real-time detection
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/DrivenPoseDetection.git
cd DrivenPoseDetection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the System

```bash
python app.py
```

> Make sure your webcam is connected and accessible.

---

## 🧪 How It Works

1. Captures video frames from the webcam.
2. Uses OpenCV and TensorFlow to detect facial and body landmarks.
3. Classifies driver state (e.g., attentive, drowsy, distracted).
4. Triggers alerts if an unwanted pose is detected.

---

## 📈 Future Enhancements

- Integrate with vehicle systems for automatic intervention
- Add support for multi-driver environments
- Improve accuracy with larger datasets
- Deploy on edge devices (e.g., Raspberry Pi)

---

## 📄 License

This project is licensed under the MIT License.
