# Ex-09-Data-Visualization-

## AIM
To Perform Data Visualization on a complex dataset and save the data to a file. 

# Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature generation and selection techniques to all the features of the data set
### STEP 4
Apply data visualization techniques to identify the patterns of the data.

# CODE
```
/* 
Name : Ranjith G.
Register Number : 212220220034
**Data Visualization - superstore.csv**
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sbn
df=pd.read_csv("Superstore.csv",encoding = 'windows-1252')
df.head()

df.info()

df.isnull().sum()

sbn.countplot(x=df['Segment'],data=df)
plt.title("Number of Sales in Segment")

sbn.barplot(x=df['City'],y=df['Profit'])
plt.title("Number of Profit in Cities")

sbn.countplot(x=df['Ship Mode'],data=df)
plt.title("Number of profits in Ship Mode")

sbn.boxplot(x=df['Region'], y=df['Sales'])
plt.title("Sales of Product based on Region")

sbn.scatterplot(x=df['Sales'], y=df['Profit'])

sbn.scatterplot(x=df['Sales'],y=df['City'],hue=df['Profit'])


sbn.scatterplot(x=df['Sales'],y=df['Profit'],hue=df['Ship Mode'])

sbn.scatterplot(x=df['Sales'],y=df['Profit'],hue=df['Region'])





*/
```
# OUPUT
## Data Visualization - superstore.csv
![1](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/c6b5c685-b15c-40b2-8948-50abf10007d7)
![2](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/c436e844-6f47-4796-8c18-76f8f5da8420)
![3](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/68c63ed6-e4e4-4fe2-a093-c43b8b7288ed)
![4](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/fa37e60b-2859-4587-abef-40a40947b326)
![5](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/a0eea68f-eaff-4a42-b388-33f3efe091ee)
![6](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/422faff2-05ac-4ac9-99b4-481cc83c353a)
![7](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/92b38d1d-3959-4585-aa0e-c4a70d0a5641)
![8](https://github.com/ranjithhacker/EXP-09-Data-visualization-II/assets/129825315/241168c2-ed8e-4ac7-94b2-d59034b280f3)


# RESULT
Thus the Data Visualization for the given dataset had been executed successfully.
