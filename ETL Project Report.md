ETL Project

Project Requirement:
Data from two or more different datasources to be extracted, transformed and loaded into another database.

ETL -  College Tution Fee Comparison Data

Objective

Collect the tution information for colleges/universities in USA. 

Extraction from Datasources
    List of colleges and universities dataset as csv file from Homeland Infrastructure Foundation-Level Data (HIFLD).
    College tution json data from api.data.gov
    Web scraping of top rated national universities in US
    
Transform
    Jupyter Notebook is used to read the csv and json files.
    From the csv file, the data regarding all the colleges were extracted and transformed into a dataframe.
    From the json file, relevant data regarding admission to all the colleges were loaded into dataframe and cleaned. 
    The dataset of top rated colleges were web scraped and transformed into pandas dataframe.
    String to numeric convertion was done by rermoving the comma.

Load
    Loaded the data tables into SQLite database


