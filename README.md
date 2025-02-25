# BSAN_6070_CA_03_Decision_Tree_Algorithm

## Description

### This code is utilizing census data in order to determine the amount of income that the person will make. Based on certain categorical variables within the census data, this code will be using decision trees in order to find the best performing model that will make an accurate decision. The data will start grouped and we start to split the data into a training group and a test group based on the flag variable. Once we do that, we will build a model to test each hyper-parameter variable. Whichever parameter returns the overall highest accuracy in each model will be used in the best final model. This model can then be used to visualize the decision tree. After that we can test any new record by running the same process and the model will make a decision based on the current decision tree. 

## Necessary Libraries and Versions

* os (Version 3.13.2)
* Numpy (Version 1.18.0)
* Collections (import Counter)
* Pandas (Version 2.2.3)
* Scikit Learn (Version 1.6.1)
* Matplot_lib (Version 3.10.0)
* Scikit Learn (DecisionTreeClassifier function from sklearn.tree) (Version 1.6.1)
* Scikit Learn (Metrics section with accuracy_score, precision_score, recall_score, f1_score, and confusion_matrix function) (Version 1.6.1)
* Scikit Learn (export_graphviz function from sklearn.tree) (Version 1.6.1)
* Time (Version 3.13.2)
* Graphviz (Version 0.20.3)
  
## Data Set and the Source

### The data set is an excel sheet with census data that is all compiled in one place. The data is already binned (or grouped together) based on certain continuous thresholds or categorical groupings. This data set was provided by Professor Arin Brahma. You can find the dataset either on this GitHub repository with census_data.csv or you can link it online at (https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true). 

## Source Code Acknowledgement

### There was no source code that was being utilized for this project. There were some pieces of the code that were given to us in the instruction pages provided by Professor Arin Brahma. I also got the idea to use the AutoViz from the TW-02 Workshop Presentation given by Sofia Brown and Henry Lisner for the BSAN 6070 class at Loyola Marymount University. 

## Software Being Used

### Google CoLab


## Installation

### In order to run this code you need to make sure the following:
* You have internet connection if you plan on getting the data from the direct link to Professor Brahma's GitHub
* If you are planning on doing it on Jupyter Notebook or Google Colab through a direct file, download the census_data.csv file and access it by using the right directory when using the read_csv function.
* Make sure that all necessary packages and libraries are installed. (There is one that is most likely not install. I left the install code for it at the very beginning of the code file)
