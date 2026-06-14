# Smart Bin System

## Project Overview

Smart Bin System is a deep learning-based waste classification project that automatically classifies waste into two categories: **Plastic Waste** and **Biological Waste**.

The project compares the performance of several state-of-the-art deep learning models, including **MobileNetV2**, **YOLOv8**, and **YOLOv11**, for smart waste management applications.

---

## Objectives

* Develop an intelligent waste classification system.
* Compare the performance of MobileNetV2, YOLOv8, and YOLOv11.
* Improve waste sorting efficiency through computer vision.
* Support environmental sustainability and smart city initiatives.

---

## Dataset

The dataset contains images of two waste categories:

* Plastic Waste
* Biological Waste

The dataset was preprocessed, augmented, and split into training, validation, and testing sets before model training.

---

## Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* YOLOv8
* YOLOv11
* OpenCV
* NumPy
* Matplotlib
* Streamlit
* Jupyter Notebook

---

## Project Structure

```text
Smart_Bin_System/
│
├── dataset/
├── dataset_split/
├── models/
├── notebooks/
├── results/
├── test_images/
│
├── live_prediction.py
├── smart_bin_camera.py
├── streamlit_web.py
├── requirements.txt
└── README.md
```

---

## Features

* Waste image classification
* Real-time camera prediction
* Model performance evaluation
* Deep learning model comparison
* Streamlit web interface
* Live prediction interface

---

## Models Evaluated

* MobileNetV2
* YOLOv8
* YOLOv11

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Chamroeun1101/Smart_Bin_System.git
cd Smart_Bin_System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Live Demo

The Streamlit web application has been deployed and can be accessed online:

**Demo Link:**
(https://smart-bin-5tpeewavzjn3qm8yicoe2l.streamlit.app/)

Users can upload an image of waste and receive a classification result through the web interface.

---

## Live Prediction

The `live_prediction.py` script performs real-time waste classification using a smartphone camera.

### Requirements

* A smartphone camera connected to the computer.
* Connection through:

  * USB-C cable, or
  * Wi-Fi connection (e.g., DroidCam/IP Webcam).

### Run

```bash
python live_prediction.py
```

Once connected, the system captures live video from the phone camera and classifies waste as Plastic or Biological in real time.


## Results

The experimental results show that deep learning models can effectively classify waste images with high accuracy. Detailed comparisons and evaluation metrics are available in the notebooks and results folders.

---

## Future Work

* Add more waste categories.
* Deploy on embedded devices.
* Improve real-time detection performance.
* Integrate IoT sensors for smart waste monitoring.
