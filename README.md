# Human Fall Detection for Elderly People Using CNN

## 📌 Project Overview

**Human Fall Detection for Elderly People Using CNN** is a deep learning and computer vision project developed to detect falls among elderly people.

The system uses a **Convolutional Neural Network (CNN)** to analyze images or video frames and classify human activity into two categories:

* **Fall**
* **No Fall**

The main purpose is to provide an automated monitoring solution that can help identify falls quickly and improve elderly safety.

---

live server
https://guardianstep-fall-detecti-uotd.arcada.app


## 👨‍💻 Author

**Mahidhar Yadav**
Artificial Intelligence and Data Science Student

---

## 🎯 Objectives

* Detect elderly falls automatically using computer vision.
* Use CNN for human activity classification.
* Reduce the time required to identify a fall.
* Support automated elderly monitoring.
* Provide a foundation for real-time emergency alert systems.

---

## 🧠 Technologies Used

* Python
* TensorFlow
* Keras
* Convolutional Neural Network (CNN)
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 🔄 System Workflow

```text
Input Image / Video
        ↓
Preprocessing
        ↓
Image Resizing & Normalization
        ↓
CNN Model
        ↓
Feature Extraction
        ↓
Classification
        ↓
Fall / No Fall
        ↓
Alert / Monitoring
```

---

## 🗂️ Dataset

The dataset contains images representing different human activities.

```text
dataset/
│
├── Fall/
│   ├── fall_001.jpg
│   ├── fall_002.jpg
│   └── ...
│
└── No_Fall/
    ├── normal_001.jpg
    ├── normal_002.jpg
    └── ...
```

The images are divided into training and testing datasets for developing and evaluating the CNN model.

---

## 🤖 CNN Model

The CNN extracts important visual features from the input images and uses them to classify whether a person has fallen.

### Model Architecture

```text
Input Image
     ↓
Convolutional Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Convolutional Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Flatten
     ↓
Dense Layer
     ↓
Dropout
     ↓
Output Layer
     ↓
Fall / No Fall
```

---

## 📁 Project Structure

```text
Human-Fall-Detection-CNN/
│
├── dataset/
│   ├── Fall/
│   └── No_Fall/
│
├── model/
│   └── fall_detection_model.h5
│
├── notebooks/
│   └── fall_detection.ipynb
│
├── src/
│   ├── train.py
│   └── predict.py
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Human-Fall-Detection-CNN.git
```

### 2. Open the Project

```bash
cd Human-Fall-Detection-CNN
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Example dependencies:

```text
tensorflow
opencv-python
numpy
matplotlib
scikit-learn
pillow
```

---

## 🚀 How to Run

### Step 1: Prepare the Dataset

Place the images into the `Fall` and `No_Fall` folders.

### Step 2: Train the CNN Model

```bash
python src/train.py
```

### Step 3: Test the Model

```bash
python src/predict.py
```

The model will classify the input as:

```text
Fall Detected
```

or

```text
No Fall Detected
```

---

## 📊 Model Evaluation

The model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help measure the performance of the fall detection system.

---

## 💡 Applications

The system can be used in:

* Elderly care centers
* Hospitals
* Smart homes
* Assisted living facilities
* Healthcare monitoring systems
* Home surveillance systems

---

## 🔮 Future Enhancements

* Real-time fall detection using CCTV cameras.
* Webcam-based live detection.
* SMS/email alerts to family members.
* IoT-based emergency notifications.
* Raspberry Pi or edge-device deployment.
* Improved CNN architectures for higher accuracy.
* Multi-person fall detection.

---

## ⚠️ Limitations

* Performance depends on the quality and diversity of the dataset.
* Poor lighting can affect detection.
* Camera angle and occlusion may reduce accuracy.
* The system is intended as a monitoring aid and not as a replacement for professional medical supervision.

---

## 🎓 Project Purpose

This project demonstrates the application of **Deep Learning and Computer Vision** to an important real-world problem: elderly fall detection.

By using CNN-based image classification, the system aims to detect falls automatically and provide a foundation for faster emergency response.

---

## 👨‍💻 Developed By

**Mahidhar Yadav**
**Artificial Intelligence and Data Science**

> *Using AI to build safer and smarter monitoring solutions.*
