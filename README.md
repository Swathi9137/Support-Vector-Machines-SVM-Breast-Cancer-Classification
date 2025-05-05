# 🧠 Task 7 - Support Vector Machines (SVM)

This repository contains the implementation for **Task 7 of the AI & ML Internship**: using **SVM for binary classification** on the Breast Cancer dataset.

---

## 🔍 Objective

Use Support Vector Machines (SVMs) for linear and non-linear classification, visualize decision boundaries, and tune hyperparameters using cross-validation.

---

## 📁 Dataset

- **Source**: Breast Cancer Dataset (`breast-cancer.csv`)
- **Target Variable**: `diagnosis` (`M` = Malignant, `B` = Benign)
- **Features**: Various cell nucleus measurements (e.g., radius, texture, smoothness)

---

## 🛠️ Tools & Libraries Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ✅ Tasks Completed

1. ✅ Loaded and preprocessed the dataset.
2. ✅ Applied PCA for 2D visualization.
3. ✅ Trained SVM with:
   - Linear kernel
   - RBF (Gaussian) kernel
4. ✅ Visualized decision boundaries in 2D.
5. ✅ Performed hyperparameter tuning (`C`, `gamma`) with `GridSearchCV`.
6. ✅ Evaluated models using 5-fold cross-validation.

---

## 📊 Results

| Model         | Accuracy | Cross-Validation Score |
|---------------|----------|------------------------|
| SVM (Linear)  | ~96%     | ~95%                   |
| SVM (RBF)     | ~97%     | ~96%                   |

✅ RBF Kernel showed slightly better performance with tuned hyperparameters.

---

## 📈 Visualizations

- PCA Projection of Features
- Decision Boundary for both Linear and RBF SVMs

> Visualizations help understand how each kernel separates the classes in 2D space.

---

## 📌 Concepts Covered

- Margin Maximization
- Kernel Trick (especially RBF)
- Overfitting control via `C`
- Role of `gamma` in RBF
- Cross-validation for reliable model evaluation


