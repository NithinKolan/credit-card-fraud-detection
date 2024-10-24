
# Credit Card Fraud Detection Project

This project aims to enhance credit card fraud detection systems through the application of advanced machine learning techniques. By analyzing transactional data, the objective is to swiftly identify and prevent fraudulent activities in real-time.

## Table of Contents
- [Project Deliverables](#project-deliverables)
- [Project Overview](#project-overview)
- [Data Visualization](#data-visualization)
- [Data Pre-processing](#data-pre-processing)
- [Model Descriptions](#model-descriptions)
- [Performance Metrics](#performance-metrics)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Model
1.  Logistic Regression Model
2.  Random Forest and Support Vector Machine Models
3.  Gradient Boosting Model

## Project Overview
The dataset provided contains information about credit card transactions, classified as fraudulent or non-fraudulent. The project applies machine learning models, including logistic regression, random forest, SVM, and gradient boosting, to detect fraudulent patterns and enhance the security of financial transactions.

The ultimate goal of this project is to:
- Detect fraudulent transactions accurately.
- Refine detection mechanisms.
- Strengthen security measures in real-time.

## Data Visualization
Various data visualizations were employed to understand the dataset better, including:
- **Bar Plots**: To assess the skewness of features.
- **Histograms**: To visualize central tendencies and distributions.
- **Correlation Heatmaps**: To explore relationships between features and remove redundancy.

## Data Pre-processing
Preprocessing steps included:
- **Data Splitting**: The dataset was split into 80% training and 20% testing.
- **Multicollinearity Handling**: Principal Component Analysis (PCA) was used to reduce dimensionality while retaining 90% of variance.
- **Class Imbalance**: Techniques like SMOTE were used to address class imbalances in fraudulent transactions.

## Model Descriptions
1. **Logistic Regression**: A simple and effective binary classifier.
2. **Random Forest**: A robust model capable of handling complex data.
3. **Support Vector Machine (SVM)**: Used with an RBF kernel for non-linear classification.
4. **Gradient Boosting**: Model optimized using hyperparameter tuning with RandomizedSearchCV.

## Performance Metrics
Model performance was assessed using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC Curve and AUC** (Area Under Curve)

## Results
- **Logistic Regression**: High precision (0.68) but low recall (0.29), indicating it missed many fraudulent transactions.
- **Random Forest**: Decent precision (0.73) but very low recall (0.17).
- **Support Vector Machine (SVM)**: Higher precision for fraud (0.78), but recall remained low (0.25).
- **Gradient Boosting**: Best recall for fraudulent transactions (0.67), but lower precision (0.34).

## Conclusion
This project demonstrates the challenge of balancing precision and recall for credit card fraud detection. While the models exhibit strong performance in identifying non-fraudulent transactions, improvements are needed to boost recall for fraudulent transactions. Gradient Boosting shows the most potential with a relatively higher recall rate, making it better suited for fraud detection compared to the other models.

## Trade-offs
- **High Precision, Low Recall**: Minimizes false positives but may miss some fraud.
- **High Recall, Low Precision**: Detects more fraud but increases false positives.

A business decision on the model's implementation would depend on balancing customer experience with the potential financial losses due to missed fraud.

---

### Authors
- **Nithin Kolan** - Applied Data Intelligence


