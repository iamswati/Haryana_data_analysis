# HARYANA DATA ANALYSIS📈📊

## Haryana - EDA

* This project is about data analysis on Covid-19 in Haryana state.
* This NoteBook starts with Exploratory Data Analysis (EDA) for the state Haryana, India. The data contains various features regarding the COVID-19 outbreak like Date, TotalSamples, etc

```
# Importing required libraries

# Matplotlib is a low level graph plotting library in python that serves as a visualization utility
import matplotlib.pyplot as plt
import matplotlib as plt
import numpy as np          # linear algebra      
import pandas as pd         # data processing, CSV file I/O (e.g. pd.read_csv)
import seaborn as sns
import warnings
warnings.filterwarnings("ignore")
```

## Split Date and create new columns
```
# New columns are created- year, month, and day
df["year"] = df["Date"].dt.year
df["month"] = df["Date"].dt.month
df["day"] = df["Date"].dt.day
df
```

## Distribution Plot on Total Number of samples, negative cases and positive cases

![TotalSample](https://user-images.githubusercontent.com/67102886/132088812-c99ff8a6-6d35-4360-be8d-0b33a62700d5.png)

![PositiveCase](https://user-images.githubusercontent.com/67102886/132088835-e2843c72-6f96-40b7-9677-aadb16f6e885.png)

![NegativeCase](https://user-images.githubusercontent.com/67102886/132088895-b3b1e6dc-4e56-44aa-bdc4-13e137896a26.png)

## Plot line graph- TotalSamples, Positive cases and Negative cases with respect to Date

![TotalSamples vs date for Haryana](https://user-images.githubusercontent.com/67102886/132088937-6d402e69-994f-4c6d-b583-326be20a683d.png)

![Negative cases vs date for Haryana](https://user-images.githubusercontent.com/67102886/132088962-f460e836-57ee-4e5c-a7e5-63d5b4dd0b70.png)

![Positive cases vs date for Haryana](https://user-images.githubusercontent.com/67102886/132088980-398d4060-32b2-4560-96b3-985496a25f03.png)

![Positive cases vs Negative cases for Haryana](https://user-images.githubusercontent.com/67102886/132088990-25fbabba-5191-4b79-8392-ad935c00da0a.png)

## Correlation

![Output](https://user-images.githubusercontent.com/67102886/132089082-21f025b9-ff3e-4bda-bad7-f880a0a03afe.png)
