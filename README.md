# Rain-prediction

Rain Prediction is an application which basically predicts will it "rain" tomorrow or not. The dataset I have used is the Rainfall dataset of Australia from kaggle.
Dataset link : https://www.kaggle.com/jsphyg/weather-dataset-rattle-package This project is tested over a lot of ml models like catboost, xgboost, random forest, support vector classifier, etc.. Out of these models catboost performed very well giving an Accuracy score of 86 better than others.

# Website Application Link 
https://rain-prediction-web-app.herokuapp.com/

# Tech
Front-End: HTML, CSS, Bootstrap

Back-End: Flask

IDE: Google collab, vscode

# Screenshots of App :
1. Home Page / Landing page

![home](https://user-images.githubusercontent.com/68839745/127016988-5c16d113-1259-471e-962c-348f0aba10ee.PNG)

2. About Will it Rain:

![about](https://user-images.githubusercontent.com/68839745/127017435-9467562b-0c70-4bed-b26f-dd28cde2ef11.PNG)

3. Project Developer 

![developer](https://user-images.githubusercontent.com/68839745/127017761-7bd704d7-5802-4987-8871-86dbe9c70a10.PNG)

4. Predictor

![predictor](https://user-images.githubusercontent.com/68839745/127017951-ebb65858-f15b-447b-9c39-8cbe501383c8.PNG)

![predict](https://user-images.githubusercontent.com/68839745/127018338-32af3b59-3a9d-4018-a3c8-cea5ac7f09f1.PNG)

5. Result 

![image](https://user-images.githubusercontent.com/68839745/127018580-227533c8-336e-498c-9582-a68ee759185e.png)

# Workflow

# Data Collection :- 
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

# Data Preprocessing:-

Handled missing values using Random Sample Imputation to maintain Distribution & Variance of data.

Categorical Value - Wind direction is handled by using Target guided encoding and rest others by One Hot Encoding and Label encoding.

Outliers are handled using boxplot and IQR.

Feature scaling was done using Standard Scaler.

Imbalanced Dataset was handled using RandomOverSampler.

# Model Creation :-

Models used :

1. RandomForestClassifier
2. CatBoostClassifier
3. LogisticRegression
4. KNeighborsClassifier
5. XGBClassifier
6. Support Vector Machine (SVM)

Out of these CatBoost gave the highest accuracy.

The conclusion were made using classification metrics.

# Model Deployment

The model is deployed using at Heroku server at :

https://rain-prediction-web-app.herokuapp.com/

# LinkedIn profile link :

https://www.linkedin.com/in/vedant-khatavkar-725894179/
