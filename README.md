# IT-SPESIALIS-DATA-ANALYTICTS
## Import,store and Export data
### Basics about ETL in data manipulation:
a. Extract is a stage for retrieving data from a data source contained such as text files, spreadsheets etc. our example already upload a CSV file in Jupiter which we put together in a folder PYTHON, then to retrieve the data we have to.Here the source code is used to read or retrieve
data that we have uploaded into Jupiter.
b. Transformation at this stage involves processing and modification
data that has been entered into Jupiter so that the data we will use use according to analysis needs. Transform this data used for cleaning, combining and changing data structures if necessary.This source code is used to clean data missing values ​​by filling in the missing values ​​so that there are no missing values there are others with missing values.
c. Load stage: This stage is the stage for storing data that is processed in
repository to be used for further analysis.So at this load stage we can process the data that we have processed save it using the source code as above, useto carry out further data analysis.

## CLEAN DATA
Clean data is a stage used to clean data from common issues like NULL values, special characters, unnecessary spaces, formatting inconsistent, and duplicate data. This stage is necessary so that the data can be processed further without shortcomings and errors
a. Handling null
Handling NULL is the process of cleaning data to replace NUL(empty value) with default value.To find out which columns have Null (value empty) then you must first look at the information from the data will be processed. From the table information above, you can see that there are columns has null values, namely the power, fuel, gear, and version columns.
b. Special Characters
Special characters are used to remove special characters
undesirable.
c. Trimming Spaces
Trimming Spaces is done to remove unnecessary spaces in columns. 
d. Inconsistent Formatting
Inconsistent Formatting is done to change data to consistent according to the data type.The image above is an example of an Inconsistent Formatting adjustment datetime from the date column. Meanwhile in the Motorbikes dataset
Marketplace did not do the following because the data was already in accordance.
e. Removing Duplicates
Removing duplicates is done to delete duplicate data.
f. Data Imputing
Imputing data is storing data that has been cleaned, for example saved in CSV form

## Organize Data
Data organization (arranging data) is the process of entering data into
groups and categories to make them easier to use so they can be accessed, processed,
and analyzed more quickly.

a) Sorting is a rearrangement process a collection of objects using certain rules. Sorting is called also as an algorithm for placing a collection of data elements into a specific order based on one or more internal keys
each element.
b) Filtering is the process of examining a data set for exclude, rearrange, or divide data according to criteria
certain.
c) Slicing is an operation used to access a portion of a sequence (sequence) such as a string, list, or tuple. This
allows you to select a subset of data from more sequences large by determining the start and end indices.
d) Transposing is an operation that changes the position of a row column and vice versa in a data or matrix. Transposing often used in data manipulation, especially in data frames (dataframes) as provided by the Pandas library in Python.
e) Appending is one of the features in python arrays which is quite Often used is the append function. This append function is useful to add the array value at the end. This function is a bit different from the insert function, where the insert function can add array value at a specific position.
f) Truncating is an operation in manipulating the data used to remove some data from the beginning or end of the dataset. This useful when you want to limit or truncate data in a dataset you according to certain conditions.

## Aggregate Data
Aggregate Data is the process of combining and summarizing data from multiple sources to produce in-depth conclusions is known as data aggregation. The purpose of data aggregation is to facilitate analysis and interpretation of large amounts of data.

a) Grouping is a technique for separating data based on criteria specifically by mapping data with groups. For perform grouping using a method called groupby(). When doing grouping there are several processes sequentially such as splitting, playing and combining.
b) Joining/merging is the process of combining two or more datasets based on a specific key or column. This allows us to combining data from several different sources into one larger and more complete dataset.
c) Summarizing is a way to summarize something document into a simpler form by taking important points in the document.
d) Pivoting is one of the many types of data visualization used and is a basic plot type in data visualization. Type This plot displays information in the form of a series of data points connected by straight line segments. Can be used on DataSet which has continuous values ​​to see the movement of data over time to time
