#  Breast Cancer Classification using Machine Learning

##  Overview
This project implements a complete machine learning pipeline to classify breast tumors as malignant or benign using biological features.

##  Dataset
- Source: scikit-learn breast cancer dataset
- Samples: 569
- Features: 30 numerical features related to cell nuclei
The dataset used in this project is included as `Breast_cancer_data.csv` for reproducibility and further analysis.

##  Workflow
1. Data Loading & Exploration  
2. Train-Test Split  
3. Feature Scaling (Standardization)  
4. Model Training:
   - Logistic Regression  
   - Random Forest  
5. Model Evaluation:
   - Accuracy  
   - Confusion Matrix  
   - ROC Curve & AUC  

##  Results

| Model | Accuracy | False Negatives |
|------|--------|----------------|
| Logistic Regression | 98.2% | 1 |
| Random Forest | 95.6% | 2 |

##  Key Insights
- Logistic Regression outperformed Random Forest  
- Dataset appears largely linearly separable  
- Important features:
  - worst area  
  - worst concave points  
  - mean radius  

##  Medical Perspective
Minimizing false negatives is critical, as missing malignant cases can be life-threatening.

##  ROC Curve
![ROC Curve](roc_curve.png)

##  Future Work
- Apply PCA for high-dimensional data  
- Use real gene expression datasets (GEO)  
- Explore deep learning approaches  

##  Author
Syed Shaeel Ahmad (Neurosciences)
