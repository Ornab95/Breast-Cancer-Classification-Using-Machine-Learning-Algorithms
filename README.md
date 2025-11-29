# Breast Cancer Classification Using Machine Learning Algorithms

This repository contains the implementation of a research project on **Breast Cancer Classification Using Machine Learning Algorithms** using the **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset.

The goal is to classify tumours as **benign** or **malignant** and compare multiple machine learning models **before and after hyperparameter tuning**.

---

## 🧾 Research Info
- **Title:** Breast Cancer Classification Using Machine Learning Algorithms
- **Authors:** Ornab Biswass, Mashruful Hasan, Md Shahadat Hossain
- **Supervisor:** Md. Mijanur Rahman, Assistant Professor, Department of CSE, Southeast University
- **Course:** CSE459 – Research Methodology
- **Institute:** Southeast University

---

## 📊 Dataset
- **Name:** Wisconsin Diagnostic Breast Cancer (WDBC)
- **Source:** Kaggle
- **Samples:** 569
- **Classes:**
  - Benign: 357 (62.7%)
  - Malignant: 212 (37.3%)
- **Features:** 30 numeric features + ID + diagnosis
- **Target:** `diagnosis` (M = malignant, B = benign)

---

## 🧠 Models Used
- Logistic Regression (LR)
- Decision Tree (DT)
- Random Forest (RF)
- K-Nearest Neighbor (KNN)
- Naive Bayes (NB)

Each model evaluated **before & after hyperparameter tuning**.

---

## 🔬 Methodology
1. Load dataset
2. Remove irrelevant columns (ID, unnamed)
3. Encode target labels
4. Standard scaling
5. Train-test split (70/30)
6. Train baseline models
7. GridSearchCV hyperparameter tuning
8. Evaluate using Accuracy, Precision, Recall, F1-score, ROC-AUC

---

## 📈 Results

### Baseline Results
| Model | Accuracy |
|-------|----------|
| Decision Tree | 93.56% |
| Random Forest | 97.08% |
| KNN | 96.49% |
| Naive Bayes | 95.91% |
| Logistic Regression | 96.49% |

### After Hyperparameter Tuning
| Model | Accuracy |
|-------|----------|
| Decision Tree | 94.15% |
| Random Forest | 97.08% |
| **KNN** | **98.83%** |
| Naive Bayes | 95.91% |
| Logistic Regression | 97.08% |

📌 **Top Model:** KNN with **98.83%** accuracy

---

## ▶️ How to Run

### Clone the repository
```bash
git clone https://github.com/Ornab95/Breast-Cancer-Classification-Using-Machine-Learning-Algorithms.git
cd Breast-Cancer-Classification-Using-Machine-Learning-Algorithms
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run script/notebook
```bash
python main.py
```
OR
```bash
jupyter notebook
```

---

## 📂 Project Structure
```
project/
│── data/
│── notebooks/
│── src/
│── Research Final Book.pdf
│── README.md
```

---

## 🙌 Acknowledgements
- Supervisor: Md. Mijanur Rahman
- Department of CSE, Southeast University
- All collaborators
