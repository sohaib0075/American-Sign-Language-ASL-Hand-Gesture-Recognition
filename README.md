# American Sign Language (ASL) Hand Gesture Recognition

This project is a deep learning-based system designed to recognize American Sign Language (ASL) hand gestures for both alphabets (A–Z) and numbers (0–9). It includes data preprocessing, background removal, model training using a Convolutional Neural Network (CNN), and evaluation.

---

## 📁 Dataset

### 1. ASL Alphabet Dataset (Raw)
🔗 [Kaggle - ASL Alphabet](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

### 2. Synthetic ASL Numbers Dataset (Raw)
🔗 [Kaggle - ASL Numbers](https://www.kaggle.com/datasets/lexset/synthetic-asl-numbers)

### 3. Combined & Preprocessed Dataset
🔗 [Google Drive - Preprocessed Data](https://drive.google.com/drive/folders/1jG2cFf8ONSbiZOjyyBLx4cHtxIszYKVQ)

---

## 🧠 Model Pipeline

### 🔧 Preprocessing
- Manual background removal using pixel-based segmentation
- Resizing & grayscale conversion
- Normalization to [0, 1]
- Balanced dataset across classes
- Train/test split

### 🔁 Postprocessing
- Decoded model predictions into corresponding gesture labels
- Evaluation with:
  - Accuracy
  - Confusion Matrix
  - F1-Score

---

## 🚀 Features

- ✅ Custom DIP-based background removal
- ✅ Random image selector with renaming utility
- ✅ Balanced dataset class distribution
- ✅ CNN-based gesture classification

---

## 📊 Evaluation (To be updated)

90% accuracy

## 🛠️ How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/asl-gesture-recognition.git
cd asl-gesture-recognition
