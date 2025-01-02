# Breast Cancer Diagnosis - Leveraging Machine Learning to Predict Tumor Malignancy
The project involves using machine learning techniques, specifically Support Vector Machines (SVMs), to analyze and classify breast cancer tumors as either malignant (cancerous) or benign (non-cancerous) based on the Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle.

Here's a summary of the performance of the classification models on the Breast Cancer Wisconsin (Diagnostic) Dataset:

Logistic Regression:

Accuracy: 0.906
Precision (Malignant): 0.36
Recall (Malignant): 0.80
F1-Score (Malignant): 0.50
Notes: Strong performance for benign cases but struggles with malignant cases due to low precision and F1-score for malignant tumors.
K-Nearest Neighbors (KNN):

Accuracy: 0.882
Precision (Malignant): 0.33
Recall (Malignant): 1.00
F1-Score (Malignant): 0.50
Notes: High recall for malignant tumors (perfect recall), but low precision and F1-score due to over-prediction of benign cases.
Decision Tree:

Accuracy: 0.976
Precision (Malignant): 0.80
Recall (Malignant): 0.80
F1-Score (Malignant): 0.80
Notes: Excellent accuracy with balanced precision and recall for both classes, performing well overall.
Naive Bayes:

Accuracy: 0.906
Precision (Malignant): 0.36
Recall (Malignant): 0.80
F1-Score (Malignant): 0.50
Notes: Similar performance to Logistic Regression with a strong performance for benign cases but struggles with malignant cases.
Support Vector Machine (SVM):

Accuracy: 0.953
Precision (Malignant): 0.57
Recall (Malignant): 0.80
F1-Score (Malignant): 0.67
Notes: Strong performance for benign cases with a reasonable balance for malignant tumor detection.
Gradient Boosting Machine (GBM):

Accuracy: 0.988
Precision (Malignant): 1.00
Recall (Malignant): 0.80
F1-Score (Malignant): 0.89
Notes: Best performance overall, with excellent precision and recall for benign tumors and strong detection of malignant tumors.
XGBoost:

Accuracy: 0.965
Precision (Malignant): 0.75
Recall (Malignant): 0.60
F1-Score (Malignant): 0.67
Notes: Solid performance with a good balance of precision and recall, though it is slightly outperformed by GBM.
Multi-Layer Perceptron (MLP):

Accuracy: 0.953
Precision (Malignant): 0.60
Recall (Malignant): 0.60
F1-Score (Malignant): 0.60
Notes: Reasonable accuracy but struggles to achieve a strong balance for malignant tumor detection.
Conclusion:

Best Model: Gradient Boosting Machine (GBM) with the highest accuracy and well-balanced precision and recall for both classes.
Overall Performance: Most models show good detection of benign tumors, but struggle with malignant tumor prediction, especially in terms of precision and F1-score. GBM stands out due to its strong performance across all metrics.
