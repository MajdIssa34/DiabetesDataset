# __Diabetes Prediction Analysis__
## 1. __Overview__
This project involves analyzing a dataset related to diabetes, aiming to predict whether an individual has diabetes based on various health metrics. The data, sourced from Kaggle, includes measurements such as the number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, body mass index (BMI), diabetes pedigree function, and age.

The main goal is to utilize different machine learning algorithms, including Logistic Regression, KNN (K-Nearest Neighbors), and others like GaussianNB, Decision Tree, SVC (Support Vector Classifier), and Random Forest, to predict diabetes presence. The effectiveness of these algorithms is evaluated based on their training and testing scores, and the best-performing model is identified through comparison.

## 2. __Dataset__
The dataset comprises several features:

a. Pregnancies: Number of times pregnant
b. Glucose: Plasma glucose concentration
c. BloodPressure: Diastolic blood pressure (mm Hg)
d. SkinThickness: Triceps skinfold thickness (mm)
e. Insulin: 2-Hour serum insulin (mu U/ml)
f. BMI: Body mass index (weight in kg/(height in m)^2)
g. DiabetesPedigreeFunction: Diabetes pedigree function
h. Age: Age in years
i. Outcome: Class variable (0 or 1, where 1 denotes diabetes)
## 3. __Approach__
The analysis begins with data preprocessing, including handling null values and zero values for specific features by replacing them with the mean. Exploratory data analysis (EDA) techniques, such as scatter plots and box plots, are used to understand the relationships between different variables and the outcome.

Several machine learning models are trained and evaluated:

+ Logistic Regression: Used as a baseline model.
+ Recursive Feature Elimination (RFE): Applied to identify the most relevant features.
+ Comparison of Models: Logistic Regression, KNN with tuned hyperparameters, GaussianNB, SVC, Decision Tree, and Random Forest models are trained. Their performance is assessed based on accuracy, confusion matrices, F1 + scores, Mean Squared Error (MSE), and R^2 scores.
## 4. __Findings and Conclusion__
The analysis concludes that Logistic Regression, particularly when using all available features, performs the best in predicting diabetes. This is followed by the Random Forest model, which also shows promising results. + The KNN model, with a specific number of neighbors, SVC, GaussianNB, and the Decision Tree model are also evaluated, with varying degrees of success.

The effectiveness of each algorithm is determined not only by its accuracy but also by the F1 score, MSE, and R^2 values. The study highlights the importance of feature selection and the impact of different models on the prediction accuracy of diabetes presence.

## 5. __Acknowledgments__
Kaggle for providing the diabetes dataset.
The various libraries and tools used in the analysis, including Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.
