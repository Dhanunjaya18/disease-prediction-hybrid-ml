# Disease Prediction Using Hybrid Machine Learning Models

This project aims to predict the presence of a disease (such as diabetes) based on medical input features using various machine learning models and a hybrid ensemble approach.

## 📊 Dataset
We used the **PIMA Indian Diabetes Dataset**, which includes 768 samples and 8 features such as:
- Glucose
- Blood Pressure
- Insulin
- BMI
- Age
- Diabetes Pedigree Function

## 🤖 Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Voting Classifier (Hybrid of the above)

## ✅ Model Comparison Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 0.72     |
| Decision Tree      | 0.70     |
| Random Forest      | 0.72     |
| **Voting Classifier** | **0.75** |

## 📌 Key Observations
- The hybrid Voting Classifier performed best with 75% accuracy.
- Random Forest was close in performance, while Decision Tree alone slightly underperformed.
- Feature scaling (StandardScaler) significantly helped in improving model accuracy.

## 📚 Learnings
- Learned to build and evaluate multiple ML models.
- Understood the power of ensemble learning.
- Learned how to tune hyperparameters using GridSearchCV.

## 🚀 Future Scope
- Implement more advanced ensemble models like XGBoost or LightGBM.
- Integrate the model into a simple web application for real-time prediction.

