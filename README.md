# data_cleaning_Tweets
In any Machine Learning process, Data Preprocessing is the first phase in which raw, dirty data are turned into clean data, allowing machine learning algorithms to be applied in a later stage. This Python package simplifies data preprocessing to just two lines of code. Simply input a CSV file containing raw data, and this library will clean the data and deliver a dataframe to which you can perform feature engineering, feature selection, and modelling.
What does this do?
Removes special character

Eliminates duplicates

Corrects anomalous column names

Attributes the data (categorical & numerical)
# Data Cleaning
Data-cleaning is a library for pre-processing data in Python. This returns the cleaned dataframe from the CSV file. It does imputation, deleting duplication and substituting special characters, among other tasks.
# Background
the dataset was scraped off twitter from 8 different authors and author identification of unknown tweets is carried out by models that is trained using labelled tweet.
the models need to be trained by features selected from the tweets. before these features were selected, the tweets were cleaned using the installed data-cleaning package
