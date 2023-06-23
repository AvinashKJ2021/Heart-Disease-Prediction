# Heart-Disease-Prediction
This a file which uses 4 models Knn, Logistic Regression,Decision Tree and Random Forest to predict if a person has a Heart Condition or not.This project focuses on predicting the likelihood of heart disease based on various features obtained from a cleaned dataset. The goal is to build and compare different machine learning models to find the most accurate prediction model.

## Dataset

The dataset used for this project contains the following variables:

1. HeartDisease: Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI).
2. BMI: Body Mass Index (BMI).
3. Smoking: Have you smoked at least 100 cigarettes in your entire life? (The answer Yes or No).
4. AlcoholDrinking: Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week).
5. Stroke: (Ever told) (you had) a stroke?
6. PhysicalHealth: Number of days during the past 30 days when physical health was not good (0-30 days).
7. MentalHealth: Number of days during the past 30 days when mental health was not good (0-30 days).
8. DiffWalking: Do you have serious difficulty walking or climbing stairs?
9. Sex: Are you male or female?
10. AgeCategory: Fourteen-level age category.
11. Race: Ethnicity.
12. Diabetic: (Ever told) (you had) diabetes?
13. PhysicalActivity: Adults who reported doing physical activity or exercise during the past 30 days other than their regular job.
14. GenHealth: General health perception.
15. SleepTime: Average number of hours of sleep in a 24-hour period.
16. Asthma: (Ever told) (you had) asthma?
17. KidneyDisease: Not including kidney stones, bladder infection, or incontinence, were you ever told you had kidney disease?
18. SkinCancer: (Ever told) (you had) skin cancer?

## Models Used

The following machine learning models were used for heart disease prediction:

1. K-Nearest Neighbors (KNN): The KNN model was refined to improve its accuracy.
2. Random Forest: Random Forest was employed as a prediction model.
3. Logistic Regression: Logistic Regression was utilized for heart disease prediction.
4. Decision Tree: Decision Tree algorithm was used as a prediction model.

## Data Preprocessing

The dataset underwent the following preprocessing steps:

1. Cleaning: The dataset was cleaned to handle missing values and remove irrelevant entries.
2. Formatting: The data was formatted to ensure consistency and proper data types.
3. Feature Encoding: One-Hot Encoder and Label Encoder were used to encode categorical features.
4. Feature Scaling: Standard Scaler was applied to scale numerical features.

## Evaluation Metrics

The following evaluation metrics were used to assess the performance of the prediction models:

- Accuracy: Measures the overall correctness of the predictions.
- Precision: Measures the proportion of true positive predictions out of all positive predictions.
- Recall: Measures the proportion of true positive predictions out of all actual positive instances.
- F1 Score: Combines precision and recall to provide a balanced measure of model performance.
- Cohen's Kappa Score: Measures the agreement between predicted and actual classes, accounting for chance agreement.
- AUC (Area Under the ROC Curve): Evaluates the model's ability to distinguish between classes.
- Confusion Matrix: A matrix showing the counts of true positive, true negative, false positive, and false negative predictions.
- ROC Curve: A graphical representation of the trade-off between true positive rate and false positive rate.

## Visualization

The project includes visualizations of the evaluation metrics and ROC curves for each model. These visualizations provide insights into the performance of the prediction models and their ability to discriminate between heart disease and non-heart disease cases.

## Conclusion

The heart disease prediction project utilized various machine learning models and evaluation techniques to predict the likelihood of heart disease based on a set of features. The performance of each model was assessed using multiple metrics, and visualizations were created to aid in result interpretation. The findings can be used to identify potential risk factors and aid in early detection and prevention of heart disease.

For more detailed information, please refer to the code and comments provided in the project files.

