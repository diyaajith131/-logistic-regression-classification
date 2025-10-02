# Logistic Regression Classifier

This project demonstrates **binary classification** using **Logistic Regression** on the Breast Cancer Wisconsin dataset.

## 📌 Project Objective
- Train a logistic regression classifier.
- Evaluate using confusion matrix, precision, recall, ROC-AUC.
- Understand sigmoid function and threshold tuning.

## 📊 Dataset
We use the **Breast Cancer Wisconsin Dataset** from UCI ML Repository / Kaggle.  
[Dataset Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## ⚙️ Tools & Libraries
- Python 3.x
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
- Seaborn

## 📂 Repository Structure
```
logistic-regression-classifier/
│── README.md
│── requirements.txt
│── data/
│    └── breast_cancer.csv
│── src/
│    └── logistic_regression.py
│── report/
│    └── report.md
│── models/
│    └── model.pkl
│── results/
│    ├── confusion_matrix.png
│    ├── roc_curve.png
│    └── metrics.txt
```

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone <your_repo_link>
   cd logistic-regression-classifier
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python src/logistic_regression.py
   ```

## 📈 Model Evaluation
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC curve

## 📖 Learning Outcomes
- Logistic Regression basics
- Binary classification workflow
- Threshold tuning
- Model evaluation metrics

---
Developed as part of **AI & ML Internship Task 4**.


## 💡 Interview Questions & Answers

**1. How does logistic regression differ from linear regression?**  
- Linear regression predicts **continuous values**.  
- Logistic regression predicts **probabilities** for classification.  

**2. What is the sigmoid function?**  
- Maps input values to range (0,1).  
- Formula: σ(z) = 1 / (1 + e^(-z))  
- Converts linear output into probability.  

**3. What is precision vs recall?**  
- **Precision** = TP / (TP + FP) → Correct positive predictions.  
- **Recall** = TP / (TP + FN) → Correctly identified positives.  

**4. What is the ROC-AUC curve?**  
- **ROC Curve** shows TPR vs FPR.  
- **AUC** measures performance (closer to 1 is better).  

**5. What is the confusion matrix?**  
- A 2x2 summary of predictions:  
  - TP, TN, FP, FN.  

**6. What happens if classes are imbalanced?**  
- Model may favor majority class.  
- Accuracy misleading → Use **Precision, Recall, F1, AUC**.  
- Fix with oversampling, undersampling, or class weights.  

**7. How do you choose the threshold?**  
- Default = 0.5.  
- Lower threshold → higher recall.  
- Higher threshold → higher precision.  

**8. Can logistic regression be used for multi-class problems?**  
- Yes, using:  
  - One-vs-Rest (OvR).  
  - Multinomial (Softmax).  
