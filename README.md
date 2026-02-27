# Experiment-10-Creation-and-uploading-Data-sets

# Experiment-9-Study-of-Pandas

# Name: Shreyanshu Behera

# PRN: 25070123149

# Batch: ENTC A1

# Title

Creation and Loading of Datasets in Python

# Aim

To study the process of creating custom datasets using dictionaries, saving them as CSV files, and loading external datasets for exploration and analysis using the Pandas library.

# Objectives

To create a custom student dataset using Python dictionaries.

To export a DataFrame into CSV format for permanent storage.

To load external CSV datasets into a Pandas DataFrame.

To perform metadata inspection and basic statistical analysis.

To understand data retrieval using loc and iloc indexing methods.

# Theory

Data analysis generally begins with either creating data manually or importing existing datasets. Python, along with the Pandas library, provides efficient tools to perform both tasks seamlessly.

Dataset Creation and Export

Datasets can be created using Python dictionaries, where keys act as column names and values represent data entries. These dictionaries can be converted into DataFrames for structured storage and analysis. The to_csv() function allows the DataFrame to be saved as a CSV file, ensuring data persistence for future use.

Loading External Datasets

The read_csv() function is widely used to import datasets stored in CSV format. It converts raw CSV data into a structured DataFrame, enabling efficient analysis of large datasets such as the Cars93 dataset without manual data entry.

Data Exploration Operations

info(): Displays a concise summary of the DataFrame, including column data types and non-null value counts.

shape: Returns the dimensions of the dataset in terms of rows and columns.

head() / tail(): Shows the first or last five records for quick data inspection.

dtypes: Lists the data type of each column, such as int64, float64, or object.

Data Retrieval Methods

Label-based Indexing (loc): Used to access rows or specific values using index labels and column names.

Integer-based Indexing (iloc): Retrieves data using numerical positions, which is useful when labels are unknown or not required.

Statistical Summaries

Basic statistical measures help describe dataset characteristics:

Mean: Represents the average value.

Median: Indicates the middle value in a sorted dataset.

Mode: Identifies the most frequently occurring value.

Applications of Dataset Management

Migration of locally created datasets into centralized storage systems.

Automated reporting by loading regularly updated CSV files.

Large-scale data analysis for comparative studies, such as automotive datasets.

Data auditing using methods like info() and shape to identify missing or incorrect entries.

# Conclusion

This experiment demonstrates the complete workflow of dataset management in Python. By creating a custom student_database.csv and loading an external dataset such as Cars93.csv, the process of both data generation and data ingestion is established. The use of statistical analysis and indexing techniques (loc and iloc) ensures that the data is not only stored efficiently but also becomes meaningful and actionable for analysis.
