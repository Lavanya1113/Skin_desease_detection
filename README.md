# 🌿 Skin Disease Detection and Remedy Suggestion

A deep learning-based web application that detects skin diseases from uploaded images and suggests appropriate plant-based remedies.

---

## 🧠 Project Overview

This project uses a **ResNet-18** convolutional neural network (trained with PyTorch) to classify skin disease images into 10 different categories and suggest a corresponding **Ayurvedic/medicinal plant remedy**.

Users can upload an image of a skin condition and get instant predictions with natural remedy suggestions.

---

## 🚀 Features

- Upload and classify skin disease images via a simple web interface
- Predicts the disease using a trained ResNet-18 model
- Suggests a relevant plant-based remedy for the predicted disease
- Achieved **85% training accuracy** and **69% test accuracy**
- Trained using data augmentation and optimization techniques

---

## 🛠️ Tech Stack

- **Model**: PyTorch (ResNet-18)
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (Bootstrap)
- **Libraries**: torchvision, PIL, matplotlib, pandas
- **Deployment**: Local Flask server

---

## 📂 Dataset Structure
dataset/ ├── train/ │ ├── class1/ │ ├── class2/ │ └── ... ├── val/ │ ├── class1/ │ ├── class2/ │ └── ... └── test/ ├── class1/ ├── class2/ └── ...
- 10 disease classes
- Images resized and normalized during preprocessing

---

## 🧪 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/skin-disease-detection.git
   cd skin-disease-detection

🌱 Sample Remedies

Predicted Disease   	Suggested Remedy
Eczema              	Aloe Vera Gel
Ringworm	            Neem Leaf Paste
Psoriasis	            Turmeric with Coconut Oil
Impetigo	            Basil (Tulsi) Extract
