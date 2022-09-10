Fetal health-MODEL TUNING

![image](https://user-images.githubusercontent.com/111189874/189400197-55d91413-226e-466a-a331-d56f794f3072.png)

1. About the daatset:

* Fetals are delivered from the womens womb and before that during the pregnancy the information about the fetus is tough to get. We can only get the information that there is a fetus and it would be delivered. So, as the information is not readily available the obstetricians who check the condition of the fetal rely on the indirect information. 
* One of the most dependent information is about the fetal heart rate and there is a restriction of electronic fetal heart monitoring that this variation is hindering the records of the accurate communication and time management.There is an another component known as the cardiotocogram which contains distinct signals and is mainly used for recordings of the fetal heart rate which is the main way through which the obstetricians rely on the information. 

2.3. Requirements:

* Python 
* jupyter notebook.
* Warnings
* Numpy
* Pandas
* matplolib
* seaborn and sklearn library.


3. Predicting Fetal Health:
* In this work, we use machine learning for the prediction of fetal health to prevent child and maternal mortality.

4. Data preparation:
* As a consequence, the Fetal dataset was used to create the dataset. This dataset is used to predict foetal health by utilising multiple characteristics such as baseline value,accelerations,fetal movement,uterine contraction,light decelerations, and so on. 

5. Data preprocessing:
* the first step would be to remove the null values which probe a problem while retrieving the accuracy of the dataset.After that the description of the dataset is required just to get an idea on it and to get a head start for the feature engineering process 


6. Scaling the data:
* Feature scaling in machine learning is one of the most critical steps during the pre-processing of data before creating a machine learning model. Scaling can make a difference between a weak machine learning model and a better one. The most common techniques of feature scaling are Normalization and Standardization. Normalization is used when we want to bound our values between two numbers, typically, between [0,1] or [-1,1]. 

![image](https://user-images.githubusercontent.com/111189874/189405107-c657a2c4-ee0a-4895-9831-b9657785722e.png)




7. Feature Engineering:
* Feature engineering plays an important role as everything from the data to the output of the same is dependent on the feature engineering which is being performed. Firstly a pie chart shown in figure 3 is being visualised which shows about the different health types of the fetal and get to know if it is a significant feature or not.

![image](https://user-images.githubusercontent.com/111189874/189405211-e68dbcba-2853-467f-b4c2-e71592d07521.png)



8. Test Train Split and Cross Validation methods:
* Train Test Split : To have unknown datapoints to test the data rather than testing with the same points with which the model was trained. This helps capture the model performance much better.

9. Building Machine Learning Models:¶:
* GridSearch:
exhaustively searches through all possible combinations of hyperparameters during training the phase. Before we proceed further, we shall cover another cross-validation (CV) methods since tuning hyperparameters via grid search is usually cross-validated to avoid overfitting. Hence, For accelerating the running GridSearchCV we set: n-splits=3, n_jobs=2.

![image](https://user-images.githubusercontent.com/111189874/189406527-c5d4f1ed-3906-4fee-a1ce-448a9f58b814.png)

* we use the K-Nearest Neighbors (KNN) & Random ForestCV for the prediction.

KNN:
![image](https://user-images.githubusercontent.com/111189874/189407840-ed81c503-70fc-4d1a-92c5-391acc62e5c0.png)

RandomForest:
![image](https://user-images.githubusercontent.com/111189874/189407963-5f485679-a00a-4fc8-9e08-cfac15b27a88.png)


10. we test the data accuracy berfor and after the modeling.

















