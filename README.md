# Logistic Regression Binary Classification

This project demonstrates **binary classification** using **Logistic Regression** on the [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

## 📌 Objective
- Build a logistic regression classifier to predict whether a tumor is **Benign (0)** or **Malignant (1)**.
- Learn key concepts of binary classification:
  - Train/Test split
  - Feature standardization
  - Sigmoid function
  - Threshold tuning
  - Evaluation metrics (confusion matrix, precision, recall, ROC-AUC)

---

## 🛠️ Tools Used
- **Python 3**
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

---

---

## 🚀 Steps in the Notebook
1. **Load & Preprocess Data**  
   - Drop unused columns (`id`, `Unnamed: 32`).  
   - Encode target variable (`M` = 1, `B` = 0).  

2. **Train/Test Split & Standardization**  
   - 80/20 split with stratification.  
   - Standardize features using `StandardScaler`.  

3. **Train Logistic Regression Model**  
   - Fit the model on training data.  
   - Predict on test data.  

4. **Evaluate Model**  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-score)  
   - ROC-AUC score & ROC curve  

5. **Threshold Tuning**  
   - Show how lowering the decision threshold changes predictions.  

6. **Sigmoid Function**  
   - Visualize the sigmoid curve to understand how logistic regression maps inputs to probabilities.  



