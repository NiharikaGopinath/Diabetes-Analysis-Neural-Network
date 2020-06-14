# Diabetes-Analysis-Neural-Network

This is my first Neural Network project. I have used the dataset 'pima-indians-diabetes' from Kaggle. This is a fully connected network with three layers.
The layers are defined using Dense class and the model is Sequential. The activation functions for the first, secon and third layers are 'ReLu','ReLu' and 'Sigmoid' respectively
The first layer has 12 nodes, second has 8 and third has 1 node.


The input parameters (x) are:
* Number of times pregnant
* Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* Diastolic blood pressure (mm Hg)
* Triceps skin fold thickness (mm)
* 2-Hour serum insulin (mu U/ml)
* Body mass index (weight in kg/(height in m)^2)
* Diabetes pedigree function
* Age (years)

The Output:
* Class variable( 0 or 1), since the prediction deals with the onset of Diabetes (binary classification problem).
