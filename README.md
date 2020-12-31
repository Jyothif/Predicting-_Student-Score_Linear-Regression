# Student score Project  Overview
This repository is demonstration of Student score prediction based on the number of study hours.

The main aim of this project is to prove the possibility of training and modeling a small dataset size and the feasibility of creating a prediction model with credible accuracy rate. This explores as well the possibility of identifying the key indicators in the small dataset,Linear Regression machine learning algorithm to evaluate them for the most accurate model.
  
 # code and resources
 
 * `Python: 3.7`

* `Packages: Numpy,Pandas,Matplotlib,Seaborn,Matplotlib`

* `Installation: by conda run prompt`

* `Jupyter Notebook: 6.0.3`

 # Data cleaning: 
 As I mentioned above this dataset is very small
 
 # EDA
 **By using matplotlib plotted the data points as below**
 * This plotting is depicting the datapoints and their accuracy of the model.
 
 ![](https://github.com/Jyothif/Predicting-_Student-Score_Linear-Regression/blob/main/images/Student%20score.png)
 
 # Model Building
 
 The model is divide into 80% and 20% as train and test dataset => test_size=0.2,  
 I divided the dataset using the scikit-learn train _test_split method
 
 # Model perfomance
 
 * Model perfomrance can be detected considering the model evaluation metrics
 
`MAE: 4.183859899002975`
`MSE : 21.598769307217406`
`RMAE : 4.647447612100367`
