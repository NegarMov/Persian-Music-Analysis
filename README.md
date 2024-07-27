<h1 align="center">Persian Music Analysis</h1>
<h6 align="center">Spring-2023 Data Mining Course Final Project at Amirkabir University of Tech.</h6>


## Introduction
The primary objective of this project is to analyse a real dataset of Persian music tracks and elicit various features from it. The project's full description (in Persian) can be found [here](https://github.com/NegarMov/Computational-Intelligence/blob/master/ANN_9831062/CI_project1%20-%20Description.pdf).

First, the data becomes ready for the regression and classification tasks throughout several steps:
1. **EDA:** This step helps us to better understand the data and gain a better understanding about its features and characteristics. For example, the value of some of the features are plotted throughout the years to identify the trends, some of them are examined per each artist, and the correlation between each pair of the features are plotted.
2. **Data Cleaning:** In this step, some of the rows containing missing values are dropped and some of them are filled using methods such as KNN.
3. **Feature Processing:** Identifying the most relevant features and preprocessing them is one of the most crucial steps in data mining tasks. In this steps some of the features are selected, nominal features are encoded, and all the selected features are normalized. These features are finally reduced using PCA and visualized.

Two main machine learning tasks are preformed on this dataset:
1. **Regression:** In this task, the popularity of the tracks are estimated using linear regression. A mean squared error of 7.96 is achieved.
2. **Classification:** In this task, the tracks are classified into traditional and non-traditional music. Accuracy, F1 score, precision, and recall metrics alongside with the confusion matrix are computed for this task. An accuracy of 82.9% is achieved using KNN and 87.7% using Random Forest.
