# EDA WEB APP

Develop an interactive web application using Streamlit that will read a provided CSV file by the user and perform some exploratory data analysis on it. The web application needs to be containerised with Docker and will be running using python.

The web application will be composed of 2 different sections:

1. Overall information of the dataset

   This section will provide the ability for the user to load a CSV file to be analysed. Once loaded, the application will convert it into a Pandas dataframe and display the information listed below.
   * Upload CSV file and load data as Pandas dataframe
   * Display header called “Overall Information”
   * Display filename
   * Display number of rows
   * Display number of columns
   * Display number of duplicated rows
   * Display number of rows with missing values
   * Display list of columns and their data type (text, numeric, date)
   * Display slider for selecting the number of rows to be displayed
   * Display top N rows (default 5 rows) of dataset
   * Display bottom N rows (default 5 rows) of dataset
   * Display N randomly sampled rows (default 5 rows) of dataset
   * Display a multi select box for choosing which text columns will be converted to datetime
     
2. Information on each numeric column
   This section will provide the ability for the user to get a better understanding of the information contained for each numeric column of the dataset.
   * Display name of column as subtitle
   * Display number of unique values
   * Display number of missing values
   * Display number of occurrence of 0 value
   * Display number of negative values
   * Display the average value
   * Display the standard deviation value
   * Display the minimum value
   * Display the maximum value
   * Display the median value
   * Display a histogram chart with maximum number of  bins: 50
   * Display a table listing the occurrences and percentage of the top 20 most frequent values
   * 



