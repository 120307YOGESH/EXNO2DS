# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
df=pd.read_csv("/content/titanic_dataset.csv")
df
```
<img width="1357" height="614" alt="image" src="https://github.com/user-attachments/assets/e1d51ffe-c15e-4bbd-8de7-617f24f6a177" />

```
df.info()
```
<img width="545" height="514" alt="image" src="https://github.com/user-attachments/assets/cffc0dd1-0d38-4242-8334-a2f69f1eb5ca" />

```
df.describe()
```
<img width="985" height="450" alt="image" src="https://github.com/user-attachments/assets/aaf0aeee-805a-4095-a689-765e3eb66aaf" />

```

```
<img width="289" height="637" alt="image" src="https://github.com/user-attachments/assets/fb38c5cb-5d55-4c83-990a-62a2e8974b62" />

# RESULT
        <<INCLUDE YOUR RESULT HERE>>
