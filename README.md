# 🧠 Digit Recognizer System (With and Without PCA)

This project demonstrates a digit recognition system using machine learning techniques. The system is evaluated in two scenarios:
1. Using the full dataset without dimensionality reduction.
2. Using Principal Component Analysis (PCA) with only 100 principal components.

---

## 📂 Dataset
- **Source:** MNIST Dataset
- **Description:** The dataset contains 70,000 images (28x28 grayscale) of handwritten digits (0 to 9).
- **Training Data:** 60,000 samples
- **Test Data:** 10,000 samples

---

## 🧪 Experiments

### 1️⃣ Without PCA (Using Full Dataset)
- **Model Used:** [e.g., Logistic Regression / Random Forest / SVM / Neural Network]
- **Training Set:** Full MNIST dataset
- **Accuracy:** 🟢 **96.48%**

### 2️⃣ With PCA (Using Only 100 Components)
- **Dimensionality Reduction:** PCA (100 principal components)
- **Model Used:** Same as above
- **Accuracy:** 🟠 **95.44%**
- **Remark:** Achieved nearly the same accuracy with a significant reduction in feature size and computational cost.

---

## 🧰 Tech Stack
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📊 Results Summary

| Experiment            | Accuracy | Components Used | Comment                                |
|----------------------|----------|------------------|----------------------------------------|
| Full Dataset (no PCA) | 96.48%   | All pixels (784) | Highest accuracy, full feature set     |
| PCA (100 components) | 95.44%   | 100             | Slightly lower accuracy, faster & efficient |

---

## 📝 Conclusion
Using PCA significantly reduces dimensionality while retaining most of the accuracy. This is especially useful for real-time or resource-constrained environments.

---
