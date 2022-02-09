# Lab project - A Beautiful Readme file

By [Lluis Badia Planes](https://github.com/lluis90badia), 9/2/2022

## The purpose of this lab is to re-submit a previous jupyter lab project, but this time to present it in a proper way (more professional). In this case, we will re-submit the lab 'Imbalance Data' (8/2/2022).

<p align = "center">
  <img src = "https://datascience.aero/wp-content/themes/yootheme/cache/imbalancedata-1a747361.png" />
</p>

## Table of contents:
- [Brief explanation of the lab](https://github.com/lluis90badia/lab_readme/blob/main/README.md#brief-explanation-of-the-lab)
- [Data files](https://github.com/lluis90badia/lab_readme/blob/main/README.md#data-files)
- [Explanation of the process](https://github.com/lluis90badia/lab_readme/blob/main/README.md#explanation-of-the-process)
- [Conclusions](https://github.com/lluis90badia/lab_readme/blob/main/README.md#conclusions)

## Brief explanation of the lab

The **purpose** is to know more about some of the methods of **measures of accuracy** and **data imbalance** to be able to measure performance and data quality (logistic regression, SMOTE, Tomek links, etc.).

The data contained in the dataframe is imbalance, that means that the column we are trying to apply those methods are not equally balanced; that is why, we have more values in one of the classes than the other. With the use of those methods, we will try to check the level of accuracy when we test and predict the data.

## Data files

The [data](https://github.com/lluis90badia/lab_readme/tree/main/CSV_files) we have used was already provided by the task in **CSV** format.

## Explanation of the process

1. First task is to import all the packages and functions from Python that we will have to use.
2. After that, we load the data from the CSV file.
3. Moving on, we select the 'Churn' column as the dependent feature and 'tenure', 'SeniorCitizen' and 'MonthlyCharges' as the independent ones to predict the independent variable using (first) Logistic Regression.
4. Then we scale the independent variables.
5. After that, we build the Logistic Regression model splitting our variables (independents and dependent) between the train and the test data. After that, we define our model with maximum 500 iterations for classification. Finally we evaluated it to check the accuracy.
6. To explain why we get that percentage of accuracy, we use the confusion matrix to determine our observed and predicted results in a more visualised way.
7. Now is the time to use the SMOTE to correct (oversampling) the imbalance between the minority until the value level of the majority class check if the level of accuracy is better than the last method.
8. Finally we do the same, but this time with the Tomek links method to reduce the majority class values that are in the border between classes and close to minority class values.

## Conclusions

As we said before in the explanation, all the steps that has been performed are key to make our data ready for the next steps (data visualisaton, Tableau, SQL, etc).
