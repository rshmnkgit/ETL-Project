ETL Project

Requirement:
Data from two or more different datasources to be extracted, transformed and loaded into another database.

ETL - 2020-21 College Tution Fee Comparison Data

Objective

Collect the 2020-21 tution information for professional colleges/universities in USA. 
Extraction from Datasources
    List of colleges and universities dataset as csv file from Homeland Infrastructure Foundation-Level Data (HIFLD).
    Web scraping of 2020-21 tution fee information from https://www.tuitiontracker.org/. This is a site where the 
    projected 2020-21 tution fee for colleges are available, which is calculated based on the tution fee data for the years 2008-09 to 2017-18.
    Extract current weather of the college locations with API calls from OpenWeatherMap
Transform
    Selection of relevant columns, removing null values, merging data
Load
    Load the data tables into SQLite database


