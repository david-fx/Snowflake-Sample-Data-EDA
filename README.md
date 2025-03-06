This repository contains a simple Exploratory Data Analysis (EDA) of sample data imported from Snowflake.

Source
Dataset: Snowflake Sample Data   ('app.snowflake.com/me-central2.gcp/az25019/#/data/databases/SNOWFLAKE_SAMPLE_DATA')

Installation
To run the analysis, you'll need to have the following libraries installed:

  snowflake-connector-python[pandas], pandas, numpy, matplotlib, seaborn

The script connects to Snowflake and imports the sample data using the snowflake-connector-python library. Here's a brief overview of the process:

1. Establish a connection to Snowflake.
2. Query the sample data.
3. Load the data into a Pandas DataFrame.
