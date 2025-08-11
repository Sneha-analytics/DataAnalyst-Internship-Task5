# DataAnalyst-Internship-Task5
# Task 5: Exploratory Data Analysis (EDA)

## **Objective**
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights, identify patterns, and understand relationships between variables using Python libraries such as Pandas, Matplotlib, and Seaborn.

## **Tools**
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## **Dataset**
Dataset: Titanic Dataset from Kaggle (https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
This dataset contains details of Titanic passengers including demographics, ticket information, and survival status.

## **Steps Performed**
1. Data Loading & Inspection:
   - Loaded the dataset and viewed initial rows using `.head()`
   - Checked data types, null values using `.info()` and `.isnull().sum()`
2. Data Cleaning:
   - Filled missing values in `Age` with median
   - Filled missing values in `Embarked` with mode
   - Dropped irrelevant columns such as `Cabin` and `Ticket`
3. Univariate Analysis:
   - Plotted histograms and countplots for single feature distributions
4. Bivariate Analysis:
   - Compared survival rates with Gender, Passenger Class, Age groups
5. Correlation Analysis:
   - Generated heatmap to identify correlation between numerical variables

## **Key Insights**
- Female passengers had a higher survival rate than males
- First-class passengers survived more compared to second and third class
- Younger passengers had higher chances of survival
- Higher fares were linked to better survival rates

## **Outcome**
This analysis provided valuable insights into the factors affecting survival rates on the Titanic, which can be used for predictive modeling.
