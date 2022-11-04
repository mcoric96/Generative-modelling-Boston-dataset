# Generative-modelling-Boston-dataset
Generative models for creating synthetic data from Boston dataset <br>

Boston dataset is preprocessed in ``` data_preparation.ipynb ``` file. <br>
Load preprocessed data from ``` boston_dataset_data.mat ``` file. <br>

## Abstract <br>
The Boston Housing Dataset (https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html) is small size dataset for benchmark machine learning algorithms. <br>
Dataset contains 506 cases, each with 14 attributes (13 numerical/categorical predictive variables and 1 one target variable: median value of owner-occupied homes in $1000's). <br>

Second and fourth column from predictors are deleted and target variable is joined to final dataset for generative modelling. <br>
Shape of final dataset ```boston_dataset_data.mat``` is ```(506,12)```. <br>

Load data with: ```ruby
boston_data = loadmat('boston_dataset_data')['boston_dataset_data']
```. <br>
