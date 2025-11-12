# Diabetes Prediction with Machine Learning
 
This project applies multiple machine learning algorithms on the **Pima Indians Diabetes dataset** to predict diabetes occurrence.  
The focus is on comparing **model performance before and after class balancing** using RandomOverSampler (oversampling).

## 🚀 Models Used
- Logistic Regression
- Support Vector Classifier (SVC)
- Random Forest Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree Classifier

## 📊 Evaluation Metrics
For each model, the following metrics are calculated:
- Accuracy
- Recall
- Precision
- F1-Score

## 🔎 Key Results
- Imbalanced data led to lower recall and F1-scores.
- After oversampling, models like **RandomForestClassifier** and **GradientBoostingClassifier** achieved significant improvements.
- Visualization shows clear performance gain after handling imbalance.

## 📈 Visualization
The project includes bar charts comparing performance **before vs after oversampling**.

## 🛠️ How to Run
```bash
git clone https://github.com/majdmibrahim/diabetes-ml-oversampling.git
cd diabetes-ml-oversampling
pip install -r requirements.txt
python main.py


📌 Requirements

Python 3.8+

scikit-learn

imbalanced-learn

pandas

matplotlib

seaborn

✨ Author

Created by Majd Ibrahim
