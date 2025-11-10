


markdown
# 🧠 Multi-Domain ML Analysis: Diabetes Classification & Soccer Player Clustering

---

**Author:** **Ogunseye Oluwajuwon**  

A comprehensive **machine learning project** demonstrating both **supervised classification** (Diabetes prediction) and **unsupervised clustering** (Soccer player segmentation) techniques.

---

## 📊 Project Overview

This project explores two distinct machine learning domains:

- 🩺 **Diabetes Prediction** → Binary classification to predict diabetes outcomes  
- ⚽ **Soccer Player Analysis** → Clustering to group players based on performance metrics  

---

## 🗂️ Dataset Information

### 1️⃣ Diabetes Dataset
- **Source:** Pima Indians Diabetes Database (Kaggle)  
- **Samples:** 768 patient records  
- **Features:** 8 medical predictors  
- **Target:** Binary outcome (`1 = diabetes`, `0 = no diabetes`)  

**Key Features**
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  

---

### 2️⃣ Soccer Players Dataset
- **Source:** FIFA 22 Player Database  
- **Samples:** 18,000+ professional players  
- **Features:** 100+ attributes including performance, value, and physical stats  

**Key Features**
- Overall rating  
- Potential  
- Value (EUR)  
- Wage (EUR)  
- Age  
- Nationality  
- Position  
- Skills  

---

## 🛠️ Installation & Setup

### ✅ Prerequisites
Make sure you have **Python 3.10+** installed.

bash
python --version


### ⚙️ Installation Steps

bash
# Clone the repository
git clone https://github.com/Juwon-Ogunseye/clustering-classification-showcase.git
cd clustering-classification-showcase

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

### 📦 Required Packages

If `requirements.txt` isn’t used, install dependencies manually:

bash
pip install pandas numpy matplotlib seaborn scikit-learn duckdb jupyter

---

## 📁 Project Structure

clustering-classification-showcase/
│
├── dataset/
│   ├── diabetes2.csv                   # Diabetes dataset
│   ├── players_22.csv                  # Soccer players dataset
│   └── Career Mode female player datasets - FIFA 16-22.xlsx
│
├── ml.ipynb                            # Main analysis notebook
├── requirements.txt                    # Project dependencies
└── README.md                           # Project documentation


---

## 🧠 Machine Learning Approaches

### 🩺 1. Diabetes Classification (Supervised Learning)

* **Algorithms:** Logistic Regression, Random Forest, SVM
* **Preprocessing:** Min-Max scaling, missing value handling
* **Evaluation Metrics:** Accuracy, Precision, Recall, Confusion Matrix

**Results**

* Accuracy: **74.7%**
* Key predictors: **Glucose levels**, **BMI**, **Age**

---

### ⚽ 2. Soccer Player Clustering (Unsupervised Learning)

* **Algorithm:** K-Means Clustering
* **Preprocessing:** Feature scaling (1–11 range), normalization
* **Evaluation:** Silhouette score, cluster interpretability

**Key Insights**

* Identified **3 distinct player groups** based on performance metrics
* Clusters represent **elite**, **average**, and **developing** players

**👨‍💻 Author:** *Ogunseye Oluwajuwon*

*For questions, suggestions, or collaborations — feel free to open an issue or reach out directly!*

---

> 🧩 *Project developed as part of the Machine Learning Portfolio by Ogunseye Oluwajuwon.*

