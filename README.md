The project is based on analysis, visualization and modeling of “Heart disease dataset” obtained from University of California Irvine machine learning repository. The dataset includes 14 unique attributes and 303 instances without any null values. Target is of categorical type, 1 for diagnosis of heart disease and 0 for no diagnosis of heart disease.  Exploration of dataset includes analytical and graphical presentation of relationship between instances, and instances with target. Three different classification algorithm namely, K-Nearest neighbor, Decision tree and Logistic regression are used for model accuracy and predicting accuracy scores. Model accuracy scores for KNN is found to be 83.60% for K = 7, Decision tree to be 85.25 % and Logistic regression to be 88.5%. f1 score are found to be 0.80 for KNN, 0.85 for decision tree and 0.89 for Logistic regression. Overall logistic regression predict more accurate accuracy score among three classifiers. Confusion matrices are also presented to observe number of true label and predicted label distribution among test sets.
Attributes Information:
age:  The person's age in years
sex: The person's sex (1 = male, 0 = female)
cp: The chest pain experienced. (Value 0: typical angina, Value 1: atypical angina, Value 2: non-anginal pain, Value 3: asymptomatic)
trestbps: The person's resting blood pressure (mm Hg on admission to the hospital), anything above 130-140 is typically cause for concern.
chol: The person's cholesterol measurement in mg/dl.
fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality(signals non-normal heart beat), 2 = Possible or definite left ventricular hypertrophy (Enlarged heart's main pumping chamber)
thalach: The person's maximum heart rate achieved
exang: Exercise induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest looks at stress of heart during exercise unhealthy heart will stress more.
slope: the slope of the peak exercise ST segment (0: Up-sloping: better heart rate with exercise (uncommon) 1: Flat-sloping: minimal change (typical healthy heart) 2: Down=sloping: signs of unhealthy heart)
ca: The number of major vessels (0-3)
thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)
target: Heart disease (0 = No, 1 = Yes)




