
# Titanic Machine Learning Model

## Index
* OverView
* Libraries Used
* Datasets Used
* Steps Performed
* Result


## OverView:

Using machine learning to create a model that predicts which passengers survived the Titanic shipwreck.


## Libraries Used:
 * pandas
 * numpy
 * sklearn.model_selection
 * train_test_split
 * sklearn.tree
 * sklearn.metrics
 * DecisionTreeClassifier
 * accuracy_score
 * recall_score
 * precision_score
 * f1_score

 ## Datasets Used:

 In this project we used a csv file which consist data of number of passengers that either lost their lives or got rescused in the same disaster.
 The data consist of 891 rows and 12 columns with different attributes present within each.


 ## Steps Performed:
 * Read the csv file and check for shape and information present within.
 * Removing the unwanted or unrelated data variables from the Datasets and coming up with the needful columns.
 * Finding null values and filling them with mean values as per the needs.
 * Since the data was straight forward the encoding was done just by replacing it with suitable numercial numbers.
 * Dividing the dataset into train and test dataset respectively using the dependent and non-dependent variables as per the requirements.
 * Using DecisionTreeClassifier model to predict the output of the dataset.
 * Saving the prediction value into an output csv file with suitable name.

 ## Result:
 Accuracy Score :0.757847533632287

 


