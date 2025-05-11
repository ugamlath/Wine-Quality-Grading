# Wine-Quality-Grading
A machine Learning model to predict if wine is " Good" or "Below_Average" based on it's physical and chemical properites using python
In this project, I built three classification models: Logistic Regression, Support Vector Machine (SVM), and Decision Tree to predict wine quality based on chemical and physical characteristics.
After evaluating the models using cross-validation, the following accuracies were observed:
Logistic Regression CV Accuracy: 0.67
SVM CV Accuracy: 0.68
Decision Tree CV Accuracy: 0.61
The Support Vector Machine (SVM) model achieved the highest cross-validation accuracy, indicating it captured the underlying patterns slightly better than the others. 
Due to limited computing resources and time constraints, hyperparameter tuning was not performed. All models were trained using default settings to ensure feasibility on available hardware.
Overall, the models provided meaningful predictive power. For future work, tuning hyperparameters and experimenting with ensemble techniques such as Random Forest or XGBoost could further improve performance.
