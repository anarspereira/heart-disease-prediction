# Sistemas Inteligentes para a Bioinformática
Repositório do projeto em grupo realizado no âmbito da UC de Sistemas Inteligentes para a Bioinformática do Mestrado em Bioinformática, 2022/2023

Grupo:
- Ana Carolina Inácio, PG45459;
- Ana Rafaela Pereira, PG45461;
- Mariana Coelho, PG45967

"Heart Attack Analysis & Prediction Dataset", a dataset for heart attack classification, available at https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset
The CSV files are the datasets used in this analysis.

## About this dataset
- age : age of the patient
- sex : sex of the patient
- cp : chest pain type
  - Value 0: typical angina
  - Value 1: atypical angina
  - Value 2: non-anginal pain
  - Value 3: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol: cholesterol in mg/dl fetched via BMI sensor
- fbs: (fasting blood sugar > 120 mg/dl)
  - 1 = true
  - 0 = false
- restecg: resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalachh: maximum heart rate achieved
- exng: exercise induced angina
  - 1 = yes
  - 0 = no
- oldpeak: ST depression induced by exercise relative to rest
- slp: the slope of the peak exercise ST segment
  - 0 = unsloping
  - 1 = flat
  - 2 = downsloping
- caa: number of major vessels (0-3)
- thall : thalassemia
  - 0 = null
  - 1 = fixed defect
  - 2 = normal
  - 3 = reversable defect
- output: diagnosis of heart disease (angiographic disease status)
  - 0: < 50% diameter narrowing. less chance of heart disease
  - 1: > 50% diameter narrowing. more chance of heart disease

## In the jupyter notebook file, you can find...
- The data pre-processing
- Exploratory data analysis
- Statistical tests and correlation
- Machine learning (Supervised learning, classification problem)
  - Model fitting (SVM, Logistic Regression and KNN models);
  - Ensemble (Bagging classifier, Random Forest and Voting Classifier);
  - Feature selection (Variance Threshold, Select K-Best and Select Percentile);
  - Hyperparameter tuning (Grid Search and Randomized Parameter Optimization).
