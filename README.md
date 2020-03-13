# machine-learning-challenge
 
 
**Background**
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.


**Preprocess the raw data**
Tune the models
Compare 3 models including base model: 

_support vector machine-linear for the baseline model_,

_support vector machine-rbf_,


as well as _lightgbm multiclass classification)_

**Steps**
Preprocess the dataset prior to fitting the model.
some eda to examine the data to see if it is *imbalanced data* and what are column types(numerical vs categorical)
Use **MinMaxScaler()/standardscaler()** to scale the numerical data.
Separate the data into training and testing data.


**Tune Model Parameters**

Used GridSearch to tune model parameters.
Tune and compare at least two different classifiers.


