# 🧠 Brain Tumor Detection from MRI Images

This project is focused on classifying **brain MRI images** into four categories:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

A **Support Vector Classifier (SVC)** with a **polynomial kernel** was used as the core machine learning model, achieving an **accuracy of 91.8%**.

---

## 📁 Project Structure

```
├── model_training.ipynb
├── README.md
└── requirements.txt
```

---

## 🔍 Problem Statement

Brain tumors can be life-threatening and require early diagnosis. Manual detection is time-consuming and error-prone. The goal of this project is to **automatically classify brain MRI scans into 4 categories** using machine learning, improving diagnosis speed and accuracy.

---

## 📊 Dataset

The dataset used contains labeled MRI scans and includes the following classes:

- **Glioma**
- **Meningioma**
- **Pituitary**
- **No Tumor**

---

## ⚙️ Model Details

- **Algorithm:** Support Vector Machine (SVC)
- **Kernel:** Polynomial
- **Accuracy Achieved:** **91.8%**
- **Preprocessing:**
  - Image resizing to a uniform size
  - Pixel normalization
- **Feature Extraction:** Flattened image arrays

---

## 📈 Performance

- **Training Accuracy:** 91.8%
- **Confusion Matrix:** Included in the notebook
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score

---

## 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/brain-tumor-classification.git
   cd brain-tumor-classification
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/model_training.ipynb
   ```

---

## 👷‍♂️ Future Improvements

- Use deep learning (CNNs) for improved feature extraction.
- Implement real-time detection via a web or mobile interface.
- Add support for 3D MRI scans.

---

## 🙌 Acknowledgements

- MRI images dataset sourced from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
- Developed as part of an academic AI/ML project on medical imaging.

