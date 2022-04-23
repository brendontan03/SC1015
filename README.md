# Suicide Prevention Squad

## About

This is a mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence). We will be researching on the possible factors that affects suicide rates and creating some models to determine which factor is the most significant. Based on the insights from the exploratory data analysis and machine learning models, we will suggest some policies to target specific factors in hopes of reducing suicide rates around the world. For a detailed walkthrough, please view the source code in the following order:

1. [Data Cleaning & Exploratory Data Analysis](https://github.com/brendontan03/SC1015/blob/main/Data%20Cleaning%20%26%20Exploratory%20Data%20Analysis.ipynb)
2. [Machine Learning models](https://github.com/brendontan03/SC1015/blob/main/Machine%20Learning%20models.ipynb)
3. [Policies](https://github.com/brendontan03/SC1015/blob/main/Policies.ipynb)

## Group Members
- Brendon Tan (Data Cleaning and Exploratory Data Analysis)
- Gerard Sin ( Machine Learning)
- Eldrick Goh (Policies and Video Narration)

## Problem Definition

- Are we able to predict which factor has the most significant impact on suicide rates?
- Which model would be the best to predict it?
- Which policies are best suited to reduce suicide rates? 

## Datasets Used
- [Main Dataset](https://www.kaggle.com/code/dornani/a-classification-analysis-on-suicide-data/notebook)
- [Education Index Dataset](https://en.wikipedia.org/wiki/Education_Index#:~:text=An%20Education%20index%20is%20a,and%20life%20expectancy%20of%20countries.)
- [Unemployment Rates Dataset](https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS?end=2020&start=1990)
- [Inflation Rates Dataset](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?end=2020&most_recent_year_desc=false&start=1990)

## Models Used

1. Linear Regression
2. Gradient Boosting
3. Logistic Regression

## Conclusion
- Not all data in the datasets are relevant, thus there is a need to remove and clean the data to make it into the desired form.
- Data found in the main dataset is not sufficient for our problem, hence we sourced for more datasets to supplement the main dataset.
- Linear regression's accuracy is too low, might be due to insufficient data.
- Gradient boosting has a much higher accuracy for training data compared to test data, meaning the model is overfitting the data.
- Logistic regression is most reliable out of the 3 models used.
- Education Index is the most significant factor affecting suicide rates based on our logistic regression model
- Policies will be focusing on how to improve education index of countries

## What we learnt from the project
- Formatting and cleaning datasets
- Pyplot for Exploratory Data Analysis
- Logistic Regression from Scikit learn
- Gradient Boosting 
- Organising code and data on GitHub Repository as well as how to write README


## References
- https://chartio.com/learn/data-analytics/what-is-exploratory-data-analysis/#:~:text=In%20data%20mining%2C%20Exploratory%20Data,us%20before%20the%20modeling%20task.
- https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html#:~:text=pyplot%20is%20a%20state%2Dbased,%2C%200.1)%20y%20%3D%20np.
- https://www.oecd.org/education/Education-Policy-Outlook-Country-Profile-Mexico-2018.pdf
- https://journals.sagepub.com/doi/pdf/10.2304/csee.2004.6.2.101
- https://medium.com/data-science-group-iitr/logistic-regression-simplified-9b4efe801389
- https://www.analyticsvidhya.com/blog/2021/09/gradient-boosting-algorithm-a-complete-guide-for-beginners/
