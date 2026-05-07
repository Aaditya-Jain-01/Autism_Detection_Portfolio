## Autism Detection for Childhood

A machine learning classification project to support early autism screening using structured behavioral data. The model is trained using **SVM** with preprocessing and feature optimization, and evaluated using **K-Fold Cross Validation**.

## ✅ Key Highlights
- Built early autism prediction model using **SVM**
- Strong evaluation using:
  - **F1-score**
  - **Precision**
  - **Recall**
- Used **K-Fold Cross Validation**
- Visualization and insights using Seaborn

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- SVM
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Problem Statement
Early autism screening is critical for timely support and better outcomes.  
This project aims to classify whether a child may show autism traits based on screening responses and features.

---

## ML Pipeline
1. Data Cleaning
2. Encoding categorical features
3. Feature scaling (important for SVM)
4. Feature selection/optimization
5. Model training using SVM
6. K-Fold Cross Validation
7. Metrics reporting + confusion matrix

---

## Evaluation
Metrics used:
- **F1-score**
- **Precision**
- **Recall**
- Confusion Matrix

---

## Repository Structure

```text
Autism-Detection-of-Early-Childhood-Screening/
├── data/                       # dataset (optional / sample)
├── notebooks/
│   └── Autism_Detection.ipynb  # full workflow notebook
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt
└── README.md


---

## How to Run

### 1) Clone Repo
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
2) Install Dependencies
pip install -r requirements.txt
3) Run Training
python src/train.py
Notebook
You can explore the full workflow in:

notebooks/Autism_Detection.ipynb
