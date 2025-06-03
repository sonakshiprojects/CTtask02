## Predictive Analysis Using Machine Learning 

This project focuses on building a predictive model to determine whether a person is diabetic based on various medical attributes. The dataset used for this analysis is the Diabetes.csv dataset available on Kaggle.

Objective:
To develop a machine learning model that can accurately predict diabetes occurrence, aiding in early diagnosis and preventive healthcare.

Dataset:
- Source: Kaggle Diabetes Dataset (https://www.kaggle.com/datasets/mathchi/diabetes-data-set)
- Attributes Include:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = Non-diabetic, 1 = Diabetic)

Key Concepts:
- Feature Selection: Used SelectKBest to identify the most relevant features for training.
- Model Training: Applied RandomForestClassifier to train the model on selected features.
- Evaluation Metrics:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

Goal:
To predict whether a patient is diabetic based on diagnostic measurements, using supervised learning techniques.

Tools & Libraries:
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualization)

Results:
The model demonstrated reliable accuracy and performance, making it a suitable tool for preliminary diabetes prediction.
