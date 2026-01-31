# students-depression-level-prediction
https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset

`Problem Statement`
-------------
>Student depression is a growing issue influenced by academic, lifestyle, and personal factors, making early identification challenging through traditional approaches. This project uses machine learning to analyze student mental health data and predict depression status.

Features:
----------
* ID: Unique identifier for each student
* Demographics: Age, Gender, City
* Academic Indicators: CGPA, Academic Pressure, Study Satisfaction
* Lifestyle & Wellbeing: Sleep Duration, Dietary Habits, Work Pressure, Job Satisfaction, Work/Study Hours
* Additional Factors: Profession, Degree, Financial Stress, Family History of Mental Illness, and whether the student has ever had suicidal thoughts

Target Variable:
--------------------
* Depression_Status: A binary indicator (0/1 or Yes/No) that denotes whether a student is experiencing depression

  * Total rows: 27,901
* Total columns: 18

steps
--------
  Student Depression dataset was loaded
→ The dataset was imported into the notebook to begin the analysis.

Dataset structure was analyzed (rows, columns, data types)
→ The size of the dataset, feature types, and numerical and categorical variables were identified.

Missing values and data quality were checked
→ Null values and inconsistencies were examined to prevent negative impact on model performance.

Categorical features were encoded
→ Text-based features such as Gender and City were converted into numerical format suitable for machine learning models.

Numerical features were scaled
→ Scaling was applied so that features with different ranges contribute equally to the model.

Input features (X) and target variable (Depression) were separated
→ Independent variables were distinguished from the target variable for prediction.

The dataset was split into training and testing sets
→ This was done to ensure unbiased and reliable model evaluation.

Multiple machine learning models were trained
→ Logistic Regression, Decision Tree, and Random Forest models were trained and compared.

Model performance was evaluated
→ Models were assessed using accuracy, precision, recall, and F1-score metrics.

The best performing model was identified
→ Logistic Regression showed the best overall performance and was selected as the final model.

Factors influencing depression were analyzed
→ Key factors such as academic pressure, sleep duration, and satisfaction levels were identified.


Image Link:-  https://github.com/riyan-cyber333/students-depression-level-prediction/blob/main/Screenshot%202026-01-31%20121456.png
