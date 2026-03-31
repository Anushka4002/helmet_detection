# 🪖 Helmet Detection System using Computer Vision

## 📌 Overview

This project implements a computer vision-based system to detect whether a person is wearing a helmet or not. It is designed to improve road safety by automatically identifying helmet violations from images or video streams.

---

## 🎯 Problem Statement

Lack of helmet usage is a major cause of severe injuries in road accidents. Manual monitoring is inefficient and not scalable.

This project aims to:

* Automate helmet detection
* Reduce human effort in monitoring
* Enable real-time safety enforcement

---

## 💡 Solution Approach

The system uses deep learning and image processing techniques to classify individuals into:

* Helmet
* No Helmet

### Workflow:

1. Capture image/video input
2. Process frames using OpenCV
3. Detect head/region of interest
4. Classify using trained model
5. Display output with bounding boxes and labels

---

## 🧠 Technologies Used

* Python
* OpenCV
* TensorFlow / PyTorch
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
helmet_detection/
│── dataset/              # Training and testing data
│── models/               # Saved trained models
│── src/                  # Source code
│   ├── train.py
│   ├── detect.py
│   └── utils.py
│── outputs/              # Output images/videos
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Anushka4002/helmet_detection.git
cd helmet_detection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run Detection

```bash
python detect.py
```

### Train Model

```bash
python train.py
```

---

## 📊 Results

* Detects helmet and no-helmet cases accurately
* Works on both images and video streams
* Outputs labeled bounding boxes

*(Add screenshots here for better presentation)*

---

## 🚧 Challenges Faced

* Dataset imbalance
* Variations in lighting conditions
* Occlusions and partial visibility

---

## 📈 Future Improvements

* Real-time CCTV integration
* License plate detection for violators
* Web/app deployment
* Use of advanced models like YOLOv8

---

## 📚 Learnings

* Hands-on experience with computer vision
* Model training and evaluation
* Data preprocessing techniques
* Handling real-world scenarios

---

## 🤝 Contribution

Contributions are welcome. Feel free to fork and improve the project.

---

## 📬 Contact

GitHub: [https://github.com/Anushka4002](https://github.com/Anushka4002)

---

## ⭐ Acknowledgment

This project was developed as part of the **Bring Your Own Project (BYOP)** initiative.



