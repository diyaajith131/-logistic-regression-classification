# Logistic Regression Report

### 🔹 Logistic Regression vs Linear Regression
- Linear Regression → continuous values
- Logistic Regression → probability (classification)

### 🔹 Sigmoid Function
- Maps values to [0,1] → used for probability in classification.

### 🔹 Evaluation Metrics
- **Confusion Matrix**: True/False positives & negatives
- **Precision**: TP / (TP+FP)
- **Recall**: TP / (TP+FN)
- **ROC-AUC**: Model’s ability to separate classes

### 🔹 Threshold Tuning
- Default threshold = 0.5
- Lower threshold → more positives (higher recall, lower precision)
- Higher threshold → fewer positives (higher precision, lower recall)

### 🔹 Imbalanced Classes
- Use class weights or sampling
- ROC-AUC is less sensitive to imbalance

### 📊 Final Evaluation
- Accuracy: ~95%
- Precision: ~96%
- Recall: ~93%
- AUC: ~0.98
