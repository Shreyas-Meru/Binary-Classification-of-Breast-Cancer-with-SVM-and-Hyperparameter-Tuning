# Binary Classification of Breast Cancer using SVM with Hyperparameter Tuning

This project demonstrates how to use **Support Vector Machines (SVM)** for binary classification of breast cancer diagnoses using the **Breast Cancer Wisconsin (Diagnostic) dataset**. It also includes **hyperparameter tuning** using `GridSearchCV` to optimize model performance.

---

## 📌 Overview

The goal of this project is to classify tumors as **malignant** or **benign** using a supervised machine learning algorithm (SVM). This is done by:

- Loading and preprocessing the dataset
- Splitting into training and testing sets
- Training an SVM model
- Performing hyperparameter tuning using grid search
- Evaluating model performance with metrics and visualizations

---

## 📁 Repository Structure

```

📦Binary-Classification-of-Breast-Cancer-with-SVM-and-Hyperparameter-Tuning
┣ 📜 Support Vector Machines.ipynb
┣ 📜 breast-cancer.csv
┣ 📜 README.md

````

---

## 📊 Dataset

- **Source**: [`Breast Cancer Dataset`](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- **Features**: 30 numeric features (mean, standard error, and worst values for attributes like radius, texture, smoothness, etc.)
- **Target**: `0 = malignant`, `1 = benign`

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn (SVM, GridSearchCV, classification metrics)

---

## 🧪 Model Training and Evaluation

The project covers:

- Feature standardization using `StandardScaler`
- SVM with a linear kernel (initial model)
- Hyperparameter tuning with `GridSearchCV` on kernel, `C`, and `gamma`
- Model evaluation using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - Visualizations of decision boundaries

---

## 📈 Results

After hyperparameter tuning, the model showed significant improvements in classification accuracy and generalization.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Shreyas-Meru/Binary-Classification-of-Breast-Cancer-with-SVM-and-Hyperparameter-Tuning.git
````

### 2. Open the notebook

Launch the `Support Vector Machines.ipynb` in Jupyter Notebook or any IDE that supports `.ipynb`.

---

## ✅ Future Improvements

* Explore additional models (e.g., Random Forest, XGBoost)
* Perform feature selection techniques
* Use cross-validation with pipelines for better reproducibility

---


## 🙋‍♂️ Author

**Shreyas Meru**
🔗 [LinkedIn](https://www.linkedin.com/in/shreyasmeru)

---

## ⭐️ If you found this helpful...

Feel free to star ⭐ the repository or fork 🍴 it for your own projects!
