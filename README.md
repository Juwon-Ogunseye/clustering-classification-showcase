```markdown
# Multi-Domain ML Analysis: Diabetes Classification & Soccer Player Clustering

**Author: Ogunseye Oluwajuwon**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-Classification%20%26%20Clustering-orange)
![Datasets](https://img.shields.io/badge/Datasets-Diabetes%20%26%20Soccer-green)

A comprehensive machine learning project by **Ogunseye Oluwajuwon** demonstrating both supervised classification (Diabetes prediction) and unsupervised clustering (Soccer player segmentation) techniques.

## 📊 Project Overview

This project explores two distinct machine learning domains:
- **Diabetes Prediction**: Binary classification to predict diabetes outcomes
- **Soccer Player Analysis**: Clustering to group players based on performance metrics

## 🗂️ Dataset Information

### 1. Diabetes Dataset
- **Source**: Pima Indians Diabetes Database
- **Samples**: 768 patient records
- **Features**: 8 medical predictors
- **Target**: Binary outcome (1 = diabetes, 0 = no diabetes)

**Key Features:**
- Pregnancies, Glucose, BloodPressure, SkinThickness
- Insulin, BMI, DiabetesPedigreeFunction, Age

### 2. Soccer Players Dataset  
- **Source**: FIFA 22 Player Database
- **Samples**: 18,000+ professional players
- **Features**: 100+ attributes including performance, value, and physical stats

**Key Features:**
- Overall rating, Potential, Value (EUR), Wage (EUR)
- Age, Nationality, Position, Skills

## 🛠️ Installation & Setup

### Prerequisites
```bash
Python 3.10+
```

### Installation
```bash
# Clone repository
git clone https://github.com/Juwon-Ogunseye/clustering-classification-showcase.git
cd clustering-classification-showcase

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Required Packages
```bash
pip install pandas numpy matplotlib seaborn scikit-learn duckdb jupyter
```

## 📁 Project Structure

```
clustering-classification-showcase/
│
├── dataset/
│   ├── diabetes2.csv                 # Diabetes dataset
│   ├── players_22.csv               # Soccer players dataset
│   └── Career Mode female player datasets - FIFA 16-22.xlsx
│
├── ml.ipynb                         # Main analysis notebook
├── requirements.txt                 # Project dependencies
└── README.md                       # Project documentation
```

## 🧠 Machine Learning Approaches

### 1. Diabetes Classification (Supervised Learning)
- **Algorithm**: Logistic Regression, Random Forest, SVM
- **Preprocessing**: Min-Max scaling, handling missing values
- **Evaluation**: Accuracy, Precision, Recall, Confusion Matrix

**Results:**
- Accuracy: 74.7%
- Key predictors: Glucose levels, BMI, Age

### 2. Soccer Player Clustering (Unsupervised Learning)
- **Algorithm**: K-Means Clustering
- **Preprocessing**: Feature scaling (1-11 range), data normalization
- **Evaluation**: Silhouette score, cluster interpretation

**Key Insights:**
- Identified 3 distinct player groups based on performance metrics
- Groups represent different player tiers and value propositions

## 🚀 Usage

### Running the Analysis
```python
# Start Jupyter notebook
jupyter notebook ml.ipynb

# Execute cells in sequence for complete analysis
```

### Key Code Sections
1. **Data Loading & Exploration**
2. **Data Preprocessing & Cleaning**
3. **Feature Engineering & Scaling**
4. **Model Training & Evaluation**
5. **Results Visualization & Interpretation**

## 📈 Results & Findings

### Diabetes Classification
- Achieved 74.7% accuracy in diabetes prediction
- Glucose levels showed strongest correlation with outcome (0.47)
- Model demonstrates good specificity but moderate recall

### Soccer Player Clustering
- Successfully identified meaningful player segments
- Groups correspond to realistic player categories (elite, average, developing)
- Features like overall rating and value were key differentiators

## 🔍 Technical Highlights

- **Data Scaling**: Custom Min-Max scaling to range [1, 11]
- **Feature Selection**: Correlation analysis for predictor importance
- **Cluster Validation**: Multiple evaluation metrics for optimal k selection
- **Visualization**: Comprehensive plots for result interpretation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:

- Additional ML algorithms
- New dataset integrations
- Performance optimizations
- Documentation improvements

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Dataset providers: Kaggle Pima Indians Diabetes Database & FIFA Player Data
- Scikit-learn community for comprehensive ML tools
- Open-source contributors to Python data science ecosystem

---

**👨‍💻 Author**: Ogunseye Oluwajuwon  

*For questions or collaborations, please open an issue or reach out directly!*

---

*Project developed as part of machine learning portfolio by Ogunseye Oluwajuwon*
```

