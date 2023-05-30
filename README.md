# Ex03-Univariate-Analysis

DATE: 

GITHUB LINK: https://github.com/saran7d/Ex03-Univariate-Analysis.git

COLAB LINK:  https://colab.research.google.com/drive/1oG_mYXX-GgfAb9nW-3iCNnoskhopq1Iy?usp=sharing


# Aim
To read the given dataset and perform univariate analysis.

# Explanation

Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm
Step1 Read the given data.

Step2 Get the information about the data.

Step3 Remove the null values from the data.

Step4 Mention the datatypes from the data.

Step5 Count the values from the data.

Step6 Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program

Developed by: Saran S S

Reg no: 212221220048

```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
print(df)

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Row ID'].value_counts()

sns.boxplot(x="Row ID", data=df)

sns.countplot(x="Row ID", data=df)

sns.distplot(df["Row ID"])

sns.histplot(x="Row ID", data=df)

```

# Output

Dataset

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/1.jpeg)



Dataset info

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/2.jpeg)



Dataset describe

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/3.jpeg)



Null value

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/4.jpeg)



Data types

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/5.jpeg)



Value count

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/6.jpeg)



Boxplot

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/7.jpeg)



Count plot

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/8.jpeg)



Distribution plot

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/9.jpeg)



Histogram plot

![](https://github.com/saran7d/Ex03-Univariate-Analysis/blob/main/99(10).jpeg)

# Result
Thus we have read the given data and performed the univariate analysis with different types of plots.
