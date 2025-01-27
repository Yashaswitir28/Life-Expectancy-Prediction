# Life-Expectancy-Prediction

Life Expectancy Prediction is a statistical analysis on factors influencing life expectancy.

# Dataset used
The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The datasets are made available to public for the purpose of health data analysis. The dataset related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. In this project we have considered data from year 2000-2015 for 193 countries for analysis. The individual data files have been merged together into a single dataset.

https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who/data

# Heat Map

![image](https://github.com/user-attachments/assets/011335ab-bc06-4378-8013-8c3e3feb1e3c)

High Positive Correlation:
Infant Deaths & Under 5 Death Rate (1.0)
Percentage Expenditure (on health) & GDP (0.96)
Polio & Diptheria immunization rates (0.97)
Thinness 5-9 years & Thinness 10-19 years (0.93)
High Negative Correlation:
Adult Mortality (btw 15-60) & Life Expectancy (-0.92)

# Use the package manager pip to install the required packages.

pip3 install numpy
pip3 install pandas
pip3 install seaborn
pip3 install matplotlib
pip3 install scipy
pip3 install scikit-learn

# Reproduce Results
All code blocks must be run in sequential manner to obtain the desired results.

--> For visualizations, EDA.ipynb

--> For building the model from scratch, Model.ipynb

# Outlier Information of all columns

Column 'life expectancy' not found in the dataset. Skipping.

---------------Adult Mortality---------------

Number of outliers: 86

Percent of data that is outlier: 2.93%

---------------infant deaths---------------

Number of outliers: 315

Percent of data that is outlier: 10.72%

---------------Alcohol---------------

Number of outliers: 3

Percent of data that is outlier: 0.10%

---------------percentage expenditure---------------

Number of outliers: 389

Percent of data that is outlier: 13.24%

---------------Hepatitis B---------------

Number of outliers: 322

Percent of data that is outlier: 10.96%

---------------Measles---------------

Number of outliers: 542

Percent of data that is outlier: 18.45%

---------------under-five deaths---------------

Number of outliers: 394

Percent of data that is outlier: 13.41%

---------------Polio---------------

Number of outliers: 279

Percent of data that is outlier: 9.50%

---------------Total expenditure---------------

Number of outliers: 51

Percent of data that is outlier: 1.74%

---------------Diphtheria---------------

Number of outliers: 298

Percent of data that is outlier: 10.14%

---------------HIV/AIDS---------------

Number of outliers: 542

Percent of data that is outlier: 18.45%

---------------GDP---------------

Number of outliers: 445

Percent of data that is outlier: 15.15%

---------------Population---------------

Number of outliers: 452

Percent of data that is outlier: 15.38%

---------------thinness  1-19 years---------------

Number of outliers: 100

Percent of data that is outlier: 3.40%

---------------thinness 5-9 years---------------

Number of outliers: 99

Percent of data that is outlier: 3.37%

---------------Income composition of resources---------------

Number of outliers: 130

Percent of data that is outlier: 4.42%

---------------Schooling---------------

Number of outliers: 77

Percent of data that is outlier: 2.62%
