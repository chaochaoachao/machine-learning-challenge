# machine-learning-challenge
 
 
**Background**
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.


**Preprocess the raw data**
Tune the models
Compare 3 models including base model: 




**_1. support vector machine-linear for the baseline model_,**
![model1](/Images/model1.PNG))



**_2. support vector machine-rbf_,**
![model2](/Images/model2.PNG)

as well as 



**_3. lightgbm multiclass classification)_**
![model3](/Images/model3.PNG)

**_feature importance from Lightgbm_**
![feature_importance](/Images/feature_importance.PNG)


**Steps**
Preprocess the dataset prior to fitting the model.
some eda to examine the data to see if it is *imbalanced data* and what are column types(numerical vs categorical)
Use **MinMaxScaler()/standardscaler()** to scale the numerical data.
Separate the data into training and testing data.


