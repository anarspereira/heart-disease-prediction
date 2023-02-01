# Sistemas Inteligentes para a Bioinformática
Repository of the Intelligent Systems for Bioinformatics Curricular Unit's group project integrated in the Master's Degree in Bioinformatics at University of Minho, 2022/2023

**Group members**:
- Ana Carolina Inácio, PG45459;
- Ana Rafaela Pereira, PG45461;
- Mariana Coelho, PG45967

**Dataset used in this project**:
"Heart Attack Analysis & Prediction Dataset", a dataset for heart attack classification, available at https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

**File explanation**:
- The heart.csv file is the dataset used in this analysis, available at https://github.com/anarspereira/heart-disease-prediction/blob/c5dda01f4a0354a3cca7dd84851695d016ef64fb/heart.csv

- The sib_heart_disease_prediction.ipynb file is the notebook in which we worked on, available at https://github.com/anarspereira/heart-disease-prediction/blob/c5dda01f4a0354a3cca7dd84851695d016ef64fb/sib_heart_disease_prediction.ipynb


Other notebooks we consulted that served as support for our work:
- https://www.kaggle.com/code/melikedilekci/heart-attack-analysis-prediction-86-7/notebook - for the exploratory data analysis and hyperparameter tuning
- https://www.kaggle.com/code/hsniyesakmak/heart-attack-analysis-prediction - for the exploratory data analysis
- https://github.com/g-shreekant/Heart-Disease-Prediction-using-Machine-Learning/blob/master/Heart_disease_prediction.ipynb - for the output final score plot

-----

## About this dataset...
- **age**: age of the patient
- **sex**: sex of the patient
- **cp**: chest pain type
  - Value 0: typical angina
  - Value 1: atypical angina
  - Value 2: non-anginal pain
  - Value 3: asymptomatic
- **trtbps**: resting blood pressure (in mm Hg)
- **chol**: cholesterol in mg/dl fetched via BMI sensor
- **fbs**: (fasting blood sugar > 120 mg/dl)
  - 1 = true
  - 0 = false
- **restecg**: resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalachh**: maximum heart rate achieved
- **exng**: exercise induced angina
  - 1 = yes
  - 0 = no
- **oldpeak**: ST depression induced by exercise relative to rest
- **slp**: the slope of the peak exercise ST segment
  - 0 = unsloping
  - 1 = flat
  - 2 = downsloping
- **caa**: number of major vessels (0-3)
- **thall**: thalassemia
  - 0 = null
  - 1 = fixed defect
  - 2 = normal
  - 3 = reversable defect
- **output**: diagnosis of heart disease (angiographic disease status) - target variable
  - 0: < 50% diameter narrowing. less chance of heart disease
  - 1: > 50% diameter narrowing. more chance of heart disease


## In the notebook, you can find...
- Data pre-processing
- Exploratory data analysis
- Statistical tests and correlation
- Supervised machine learning (classification problem)
  - Model fitting (SVM, Logistic Regression and KNN models);
  - Ensemble (Bagging classifier, Random Forest and Voting Classifier);
  - Feature selection (Variance Threshold, Select K-Best and Select Percentile);
  - Hyperparameter tuning (Grid Search and Randomized Parameter Optimization).
- Deep learning (Neural Network)

-----

# Conclusions
![transferir](https://user-images.githubusercontent.com/98289507/216116177-e249240d-4563-4d9b-b67b-4c684c66bf26.png)

The Logistic Regression model performed best compared to the other algorithms. Apart from the latter, the Random Forest and Support Vector Machine models scored above 80%.

The K-Nearest Neighbors, Decision Tree and Neural Network models had the lowest scores.

Due to the shape of the dataset, we were unable to perform any further analysis, namely the unsupervised learning clustering analysis.

A future approach could be to use the XGBoost classifier algorithm and explore cross validation, hyperparameter tuning and neural networks in more depth.
