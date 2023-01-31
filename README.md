# Car-Evaluation-By-Decision-Tree-Classifier
This code is for performing Exploratory Data Analysis (EDA) on a car evaluation dataset. The code performs the following steps:

Import Libraries:
Import the required libraries including numpy, pandas, matplotlib, seaborn and warnings. The code also uses the '%matplotlib inline' command to display plots within the Jupyter Notebook.
Import Dataset:
Load the car evaluation dataset into a pandas dataframe 'df' using the 'pd.read_csv()' function.
Exploratory Data Analysis:
Check the dimensions of the dataset using 'df.shape' to determine the number of instances and variables in the dataset.
Preview the top 5 rows of the dataset using 'df.head()' to get an initial understanding of the data.
Rename the columns of the dataframe to meaningful names using the 'col_names' variable and the 'df.columns' attribute.
Get a summary of the dataset using the 'df.info()' function.
Check the frequency counts of the categorical variables using a for loop and the 'df[col].value_counts()' function.
Check the distribution of the target variable 'class' using the 'df['class'].value_counts()' function.
Check for missing values in the dataset using the 'df.isnull().sum()' function.
The output of the code provides a comprehensive summary of the car evaluation dataset, including the distribution of values in the variables and the distribution of the target variable 'class'.
