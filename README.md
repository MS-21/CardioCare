# CardioCare
CardioCare is a machine learning-based system designed to assess the risk of cardiovascular diseases using health parameters. It utilizes multiple classification models to predict disease risk and provide insights into key health indicators.

## Dataset
The dataset used for this project is sourced from Kaggle. It contains various health attributes such as:
Age, Gender
Blood Pressure
Cholesterol Levels
Smoking & Alcohol Consumption
BMI & Physical Activity
Heart Rate & Diabetes Status
## Data Preprocessing
- Handling Missing Values: Removed or imputed missing values where necessary.
- Feature Selection: Dropped unnecessary columns.
- Standardization: Used StandardScaler to normalize numerical features.
- Train-Test Split: Divided data into training and testing sets.
## Machine Learning Models Used
-CardioCare implements multiple machine learning classifiers for risk assessment:
-Logistic Regression
-Random Forest Classifier
-HistGradientBoosting Classifier
-SGD Classifier
Each model is evaluated based on accuracy, confusion matrix, and ROC-AUC score.
## Model Training & Evaluation
-The models were trained using the preprocessed dataset, and their performance was evaluated using the following metrics:
-Accuracy Score: Measures how many predictions were correct.
-Confusion Matrix: Helps analyze true positives, false positives, etc.
-Classification Report: Includes precision, recall, and F1-score.
-ROC-AUC Score: Evaluates model performance in distinguishing classes.
## Results
-The Random Forest Classifier performed the best with a high accuracy and AUC score.
-The Logistic Regression model also showed competitive results.
