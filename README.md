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

1. First task is to read using Pandas the three files into Python as dataframes.
2. After that, standarise the header names (to lowercase) all the files.
3. Then rearrange the name of the columns for an easier understanding in one of the files.
4. After that, concatenate the three dataframes into only one using the function concat().
5. Then find out which columns are numericals and which are categoricals.
6. Finally, we perform the data cleaning operations (deleting columns, checking for duplicate rows, etc.)

## Conclusions

As we said before in the explanation, all the steps that has been performed are key to make our data ready for the next steps (data visualisaton, Tableau, SQL, etc).
