# 🧠 Alzheimer's Dementia Detection using Deep Learning

A deep learning project for automated Alzheimer's disease detection from MRI brain scans using a **3-layer Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**. The model is trained on the **OASIS-2** dataset and includes MRI preprocessing, classification, and Explainable AI using **LIME**.

---

## 📌 Overview

Early diagnosis of Alzheimer's disease is crucial for effective treatment and patient care. This project leverages deep learning techniques to classify MRI brain scans into different stages of Alzheimer's dementia.

The project includes:

- MRI image preprocessing
- 3-layer CNN architecture
- Model training and evaluation
- Explainable AI (LIME) for prediction visualization

---

## 🚀 Features

- 🧠 Alzheimer's disease classification using MRI brain scans
- 📊 Three-class prediction:
  - Non-Demented
  - Mildly Demented
  - Demented
- 🖼️ MRI preprocessing from 3D NIfTI scans
- 🤖 Custom 3-layer CNN built using TensorFlow/Keras
- 📈 Training visualization with Accuracy & Loss curves
- 🔍 Explainable AI using LIME

---

## 📂 Dataset

**Dataset:** OASIS-2 (Open Access Series of Imaging Studies)

- 150 Subjects
- 373 MRI Sessions
- MRI Brain Scans
- Clinical Dementia Rating (CDR)

---

## 🏗️ CNN Architecture

```
Input (256 × 256 × 1)

        │
        ▼
Conv2D (32 Filters)
        │
MaxPooling
        │
        ▼
Conv2D (64 Filters)
        │
MaxPooling
        │
        ▼
Conv2D (128 Filters)
        │
MaxPooling
        │
        ▼
Flatten
        │
Dense (128)
        │
Dropout (0.5)
        │
Dense (16)
        │
Softmax (3 Classes)
```

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- NiBabel
- Scikit-learn
- Matplotlib
- OpenCV
- LIME

---

## 📊 Results

| Metric | Value |
|---------|--------|
| Accuracy | **96.8%** |
| Classes | 3 |
| Dataset | OASIS-2 |
| Subjects | 150 |
| MRI Sessions | 373 |

---

## 📁 Project Structure

```
├── Dataset/
├── Model_Checkpoints/
├── notebook.ipynb
├── helper.py
├── README.md
└── requirements.txt
```

---

# 📷 Project Images

> Upload the extracted images into an `images/` folder in your repository and update the filenames if needed.

## CNN Architecture
<IPython.core.display.Image object><img width="507" height="1291" alt="image" src="https://github.com/user-attachments/assets/7440f928-9e0a-4b32-a1ab-c8ae1ea4775e" />


---

## Training Accuracy

<img width="748" height="540" alt="image" src="https://github.com/user-attachments/assets/ad5f1386-cbc4-425c-a094-823f07d58896" />


---

## Training Loss

<img width="690" height="532" alt="image" src="https://github.com/user-attachments/assets/d04ce54d-2d88-4c40-b9e0-06662815f2f0" />


---

## Confusion Matrix

<img width="852" height="582" alt="image" src="https://github.com/user-attachments/assets/aa2d365d-e05a-4482-bace-bdee083c41bc" />

---

## Prediction Examples

<Figure size 1500x1000 with 15 Axes><img width="1490" height="987" alt="image" src="https://github.com/user-attachments/assets/5b0b1b15-dc09-4d6f-abe6-7f7672486164" />


---

## Future Improvements

- Implement Grad-CAM visualization
- Integrate SHAP for feature explanations
- Apply Transfer Learning (ResNet/EfficientNet)
- Train on larger datasets (ADNI)
- Deploy as a web application using Streamlit

---
