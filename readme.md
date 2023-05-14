##Kaggle Titanic Competition

This project is my practice of basic Machine Learning by making submissions for the Kaggle Titanic competition. The goal of the competition is to predict whether passengers aboard the Titanic survived or not based on various features such as age, gender, passenger class, etc.

###Dataset

The dataset used for this project can be obtained from the Kaggle competition page: https://www.kaggle.com/competitions/titanic/data. It consists of two separate CSV files: train.csv and test.csv. The train.csv file is used for training and building the machine learning model, while the test.csv file is used for making predictions on unseen data.

###Dependencies
Python 3.7+
pandas
numpy
seaborn
matplotlib
missingno
scikit-learn
xgboost
lightgbm

###Steps and studying areas:

####Observe the data (data_research notebook)
Exploring libraries for reading, analysing and visualising data.

####Cleaning the data (data_cleaning notebook)
Using different methods to find and get rid of outliers and NaNs (drop / replace with mean)

####Data preprocessing (data_preprocessing notebook)
Generating new features, encoding categorical features with LabelEncoder.

####Implementing models (model_fitting notebook)
Here are the models I used:  

                      Accuracy
Random Forest         0.842697
SVC                   0.831461
XGBoost tuned         0.823970
KNeighborsClassifier  0.812734
logistic regression   0.801498
XGBoost               0.801498
Linear SVC            0.797753

Best public score: Random Forest (0.77511)


###Sources and tutorials I used while working on the project:
Kaggle setup: https://www.kaggle.com/code/alexisbcook/titanic-tutorial
Kaggle ML competition tutorial: https://www.kaggle.com/code/alexisbcook/machine-learning-competitions/tutorial
Data preprocessing and model fitting tutorial: https://www.kaggle.com/code/guecoraph/titanic-data-cleaning-model-fitting
Assistance: https://chat.openai.com


###TODO

* Learn more about features encoding;
* Tune the remained untuned models;
* Code refactoring.


