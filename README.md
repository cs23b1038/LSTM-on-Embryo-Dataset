# 🧬 Embryo Development Stage Classification using CNN + LSTM

## 📌 Overview

This project implements a **deep learning pipeline** to classify embryo developmental stages using **time-lapse image sequences**. It combines:

* 🧠 CNN (ResNet) for spatial feature extraction
* 🔁 LSTM for temporal sequence modeling

The model predicts the **stage of embryo development** from sequential frames.

---

## 🎯 Objectives

* Automate embryo stage classification
* Capture temporal progression using LSTM
* Handle class imbalance
* Improve predictions using ordinal relationships

---

## 🗂 Dataset Structure

```
dataset/
│
├── images/
│   ├── embryo_1/
│   │   ├── frame_001.jpg
│   │   ├── frame_002.jpg
│   │   └── ...
│   ├── embryo_2/
│
├── annotations/
│   ├── embryo_1.csv
│   ├── embryo_2.csv
```

### CSV Format

```
stage,start_frame,end_frame
t2,10,20
t3,21,35
```

---

## 🧪 Classes

```
tPB2, tPNa, tPNf, t2, t3, t4, t5, t6,
t7, t8, t9+, tM, tSB, tB, tEB, tHB
```

---




## 📊 Output

* Classification report
* Confusion matrix
* Trained CNN+LSTM model

---

## 💡 Future Work

* Transformer-based sequence modeling
* Attention mechanisms
* Real-time embryo grading

---


