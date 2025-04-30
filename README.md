# Heart Disease Prediction using Logistic Regression

This project uses a logistic regression model to predict the presence of heart disease based on a dataset from the UCI Machine Learning Repository. 
The project includes data preprocessing, model training, evaluation using various metrics, and visualization of results such as confusion matrix, ROC curve, and precision-recall curve.
---

##  Dataset

- **Source**: [UCI Heart Disease Dataset (Cleveland subset)](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Features**: 13 clinical attributes (age, cholesterol, blood pressure, etc.)
- **Target**: Binary classification — `0` (no disease), `1` (disease)

---

##  Tools & Libraries

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

---

##  Machine Learning Model

###  Algorithm
- **Logistic Regression**
- Optimized using:
  - Feature scaling (StandardScaler)
  - Threshold tuning
  - ROC & PR curve analysis

---

##  Workflow

1. **Data Loading**
   - Load dataset from URL
   - Replace `?` with NaN and fill using column median

2. **Data Preprocessing**
   - Convert target to binary
   - Split into train/test sets (75%/25%)
   - Apply standard scaling

3. **Model Training**
   - Fit logistic regression with `max_iter=1000`
   - Predict class and probability

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1 Score
   - ROC AUC Score
   - Confusion Matrix
   - Classification Report
   - Threshold tuning (0.3 to 0.7)

5. **Visualizations**
   - Confusion Matrix (heatmap)
   - ROC Curve
   - Precision-Recall Curve
   - Sigmoid function plot
   - Metrics vs. Threshold line plot

---
