# 🧠 SVM Classification on the Digits Dataset

This project applies a **Support Vector Machine (SVM)** with an RBF kernel to the classic **scikit-learn Digits dataset**. The dataset contains grayscale images of handwritten digits (0–9), and our goal is to build a high-performing, interpretable, and educational classification pipeline.

---

## 🔍 Project Overview

- **Dataset:** scikit-learn's `load_digits()`  
- **Model:** SVM (RBF kernel, `C=10`, `gamma='scale'`)  
- **Classes:** 10 (Digits 0 to 9)  
- **Accuracy:** 98%  
- **Macro AUC:** 1.00  

We include powerful visualizations such as:
- Confusion Matrix  
- t-SNE projection  
- Multi-Class ROC Curve (One-vs-Rest)  
- Permutation Importance  

---

## 📂 Key Features

- End-to-end ML pipeline using classical SVM
- Pixel-wise feature importance using permutation method
- Dimensionality reduction using t-SNE for visual interpretation
- Multi-class macro ROC-AUC curve to analyze performance
- Stratified train-test splitting and scaling with `StandardScaler`

---

## 🧪 Performance Summary

| Metric             | Score     |
|--------------------|-----------|
| Accuracy           | 98%       |
| Macro Precision    | ~0.98     |
| Macro Recall       | ~0.98     |
| AUC (macro avg)    | 1.00      |

Confusion matrix shows very few misclassifications (mainly around visually similar digits like 1 vs. 7).

---

## 📈 Visualizations

- 📊 **Confusion Matrix:** Highlights diagonal dominance  
- 🌐 **t-SNE Plot:** Shows clear clustering of digits in 2D  
- 🎯 **Multi-Class ROC Curve:** Macro-averaged AUC = 1.00  
- 🧩 **Permutation Importance:** Identifies key pixels that contribute to classification

---

## 🛠️ How to Run

### 🔧 Installation

```bash
git clone https://github.com/yourusername/SVM-Digits-Classification.git
cd SVM-Digits-Classification
