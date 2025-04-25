 Titanic Survival Prediction - Machine Learning Project
 🎯 Objective
To develop a classification model that predicts whether a passenger survived the Titanic disaster using machine learning techniques.
 📂 Dataset
The dataset includes the following features:
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)


 🧹 Data Preprocessing
- Handled missing values:
  - `Age`: Filled with median
  - `Fare`: Filled with median
  - `Embarked`: Filled with mode
  - `Cabin`: Dropped or encoded (depending on experiment)
- Encoded categorical variables using:
  - `LabelEncoder` for binary features
  - `OneHotEncoder` for multi-category features
- Normalized numerical features using `StandardScaler`



 🧠 Model Selection
Trained multiple classification models:
- ✅ Logistic Regression
- ✅ Random Forest Classifier
- ✅ XGBoost Classifier

Random Forest showed the best performance on test data.



 📈 Model Evaluation
Models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Example (Random Forest):
