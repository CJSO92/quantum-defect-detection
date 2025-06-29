# quantum-defect-detection
Quantum vs Classical algorithms for defect detection using industrial images

# Quantum vs Classical Defect Detection

This project explores the use of **quantum machine learning algorithms** to detect defects in industrial objects, and compares their performance against traditional **classical machine learning** models.

We use a subset of the [MVTec AD Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad), focusing on four object types: `cable`, `grid`, `metal nut`, and `transistor`.

---

## 🧠 Objectives

- Preprocess defect/non-defect images into numerical features
- Train and evaluate:
  - Classical models (e.g. Logistic Regression, Random Forest)
  - Quantum models (Quantum Neural Network, Quantum SVM)
- Compare performance using metrics like **accuracy**, **precision**, and **recall**
- Highlight pros/cons of quantum approaches on small real-world datasets

---

## 🛠️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/CJSO92/quantum-defect-detection.git
   cd quantum-defect-detection
