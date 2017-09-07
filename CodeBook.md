title : "GettingAndCleaningData"

---
title: 'Getting and Cleaning DAta'
author: "VibhorVyas"
date: "September 7, 2017"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

###While creating the file we first need to install packages 
data.table  
reshape2  
Inital if condition shows if packages are already installed then dont install them again.  
1^st^ step is to read the table from activity_labels.txt  
2^nd^ step is to read the table from features.txt   
3^rd^ step is to extract only the measurements on the mean and standard deviation for each measurement.  
4^th^ step is to load and process X_test & y_test data.   
5^th^ Step is to extract only the measurements on the mean and standard deviation for each measurement.   
6^th^ Step is to Load activity labels.  
7^th^ step is to Bind data using cBind.  
8^th^ step is to Load and process X_train & y_train data.  
9^th^ step is to Extract only the measurgements on the mean and standard deviation for each measurement.  
10^th^ step is to Load activity data.  
11^th^ step is to Merge test and train data  
12^th^ step is to Apply mean function to dataset using dcast function.  
13^th^ step is to create final tidy_data.txt file



