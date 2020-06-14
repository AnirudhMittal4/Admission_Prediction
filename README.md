# Admission_Prediction
## Introduction
Every year thousands of students apply to universities in the US for their master's degree. The process of selecting a university is tedious and time-consuming as there are a lot of factors that are considered while applying to a university. Using this dataset we plan to understand the student selection model used by one of the most reputed colleges in the USA- UCLA. This model will help students understand the weight of each type p-score in the final decision and also how they can together influence the chances of any student getting an admit from the university of their choice.
Our analysis will consist of three stages. The first stage of data will be preprocessed. However, there are various analyses and graphs. In the next step, the weight of each variable will be showcased by using many supervised algorithms. Then we will reverse engineer the model that UCLA uses.

## 1. About the DataSet

This dataset is inspired by the UCLA Graduate Dataset. The test scores and GPA are in the older format. The dataset is owned by Mohan S Acharya. We have obtained the same from Mr. Mohan contribution on Kaggle
This dataset link is below:
https://www.kaggle.com/mohansacharya/graduate-admissions

## 2. Features in the dataset

The dataset contains several parameters which are considered important during the application for Masters Programs in a US university.
The features included are:
GRE Scores (290 to 340)
TOEFL Scores (92 to 120)
University Rating (1 to 5)
Statement of Purpose (1 to 5)
Letter of Recommendation Strength (1 to 5)
Undergraduate CGPA (6.8 to 9.92)
Research Experience (0 or 1)
Chance of Admit (0.34 to 0.97)

## 3. Pre Processing and data exploration

Taking a look at our dataset for understanding:
Using the describe function to understand the values present in each variable:

![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.30.16%20PM.png)

Correlation of the Variables:
A high correlation is visible in most of the variables. Values are ranging from .40-.84. Hence any interpretations of the coefficient values needs to be done with caution.

![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.30.10%20PM.png)

![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.11%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.15%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.24%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.29%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.34%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.42%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.48%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.54%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.31.58%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.08%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.16%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.03%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.07%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.12%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.28%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.35%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.33.56%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.34.58%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.12%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.30%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.38%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.32.45%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.46.19%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.46.24%20PM.png)
![](https://github.umn.edu/MITTA098/Admission_Prediction/blob/master/Screen%20Shot%202020-06-13%20at%201.46.34%20PM.png)
