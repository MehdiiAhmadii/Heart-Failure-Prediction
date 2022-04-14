# Heart-Failure-Prediction

Cardiovascular diseases (CVDs) cause almost 18 million death each year around the world.
80 % of CVD deaths are due to heart attack. Heart failure is a common issue caused by CVD. 
This heart failure is related to people’s attributes (age, sex, etc.). The used data set hear 
relates heart failure to these features. More specifically, the dataset contains 11 features
that try to relate human features to a heart attack. These features are as follows:

1: Age: age of the patient [years]
2: Sex: sex of the patient [M: Male, F: Female]
3: ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: ymptomatic]
4: RestingBP: resting blood pressure [mm Hg]
5: Cholesterol: serum cholesterol [mm/dl]
6: FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7: RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8: MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9: ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10: Oldpeak: oldpeak = ST [Numeric value measured in depression]
11: ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

All these features have their own effects on Heart Disease which has been used as a label as follows:
HeartDisease: output class [1: heart disease, 0: Normal]

The used data sources are as follows:
Data main source: https://archive.ics.uci.edu/ml/datasets/Heart+Disease
I downloaded it from Kaggle: https://www.kaggle.com/fedesoriano/heart-failure-prediction

Here, after some data engineering (Dealing with missing and categorical variables, outliers, EDA etc.) 
few methods including SVM, regression, and Gradient Boosting were used for classification. GradientBoostingClassifier
revealed the best predictions and was used for deployment.
