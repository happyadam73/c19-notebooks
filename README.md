# Data Visualisation of COVID-19 in the UK using Sqlite, Pandas and Seaborn Libraries 

This is a 3-part series of Jupyter Notebooks which explores the UK Gov's COVID-19 dashboard data which is publically available for download via a REST API from gov.uk.  We make use of a Sqlite3 database to query this data using SQL and import aggregations into Pandas data frames.  We then use the Seaborn library to visualise the results.

The Part 1 Notebook sets up the database from scratch and creates a set of empty tables required for storing the data.  Part 2 then looks at loading the data using the GOV.UK REST API.  Finally Part 3 will then query and visualise the data using the Seaborn and Plotly Express libraries.

The data used in this notebook is publically available and more information can be found here:
https://coronavirus.data.gov.uk/details/about-data

## Dependencies
There are several libraries that are required as listed in the requirements.txt file.

## Quick Start
A compressed copy of the C19 database is included in this repository so you do not need to run Parts 1 and 2 to extract and load the data (this can take considerable time using the GOV.UK API since it is rate limited).

To run through the visualisations of the data, simply use the following Binder URL:
https://mybinder.org/v2/gh/happyadam73/c19-notebooks/main
