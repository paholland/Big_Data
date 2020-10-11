## Big_Data - Can you handle big data?


    To perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. To use PySpark or SQL to perform a statistical analysis of selected data.
    

Created DataFrames to match production-ready tables from two big Amazon customer review datasets. Analyzed whether reviews from Amazon's Vine program are trustworthy.
The deployed assignment utilizes AWS and the PySpark library to complete 1 of 2 levels of challenges.

Extract (In both notebooks connects to and loads in datasets from AWS to dataframes using pyspark. Correctly handles the header and has column names as the first row. Ensures the data is retrieved by outputting the head of the dataframe. Discovers the size of the dataframe by outputting the number of rows in it.)

Transform & Load
Transform (Removed duplicate rows. Kept and renamed only necessary columns to match the current database table schema. Matched dataframe column types with the database column types.)
Load (Successfully pushed dataframes to AWS. Connected to and loaded in datasets from AWS to dataframes using Spark. Removed any unnecessary columns. Dropped rows with null values. Dropped duplicated rows.)

Analysis (Splits the reviews between vine (paid) and non-vine (unpaid). Compares metrics between vine and non-vine reviews such as, but not limited to: [Number of reviews
Number of 5-star reviews. Average Rating. Number of helpful votes]. Comes up with a conclusion on the trustworthiness of vine reviews with data to back up their claim.


