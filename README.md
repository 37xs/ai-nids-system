# 🛡️ AI-Powered Network Intrusion Detection System (NIDS)

This repository contains a Machine Learning-based Network Intrusion Detection System (NIDS) designed to analyze network traffic and detect malicious behavior using real IoT datasets. The system is built in Python using Jupyter Notebook and includes a variety of supervised ML models.

---

## 🎯 Objectives

- Load and process labeled network traffic datasets.
- Train multiple ML classifiers on real-world IoT network data.
- Predict and classify malicious activity vs normal traffic.
- Visualize confusion matrices and model performance.

---

## 📂 Datasets Used

### 📌 [RT-IoT2022 Dataset](https://www.kaggle.com/datasets/joebeachcapital/real-time-internet-of-things-rt-iot2022)
- Contains real-world IoT traffic with various attack types.
- Features include: Protocols, IPs, ports, packet lengths, attack types, timestamps, payloads, device info, geolocation, and more.

### 📌 [Smaller Dataset from CICIoT2023](https://www.kaggle.com/code/madhavmalhotra/creating-a-smaller-dataset-for-ciciot2023)
- A downsampled version of the CICIoT2023 dataset.
- Useful for quick experiments with balanced class distribution.

> 📁 Make sure to download and place the datasets in your working directory:
- `RT_IOT2022.csv`
- `CICIoT2023_sample.csv` or similar

---

## 🧠 Machine Learning Models Applied

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

All models are evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 📊 Sample Results

### 🔹 Confusion Matrix
![Confusion Matrix](img/confusion_matrix.png)

### 🔹 GoldenEye Attack Detection
![GoldenEye](img/goldeneye_result.png)

### 🔹 Port Scan Visualization
![Port Scan](img/portscan.gif)

> All results are generated during testing on selected dataset files.

---

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/37xs/ai-nids-system.git
cd ai-nids-system
