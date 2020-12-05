# Find a college that's right for you
### An ETL-Project on College Admission and Cost 
## Project Requirement:
Data from two or more different datasources to be extracted, transformed and loaded into another database.


How many colleges/unviersities are there in United States? How many of them are public, how many are private?
What are the subjects offered in these institutions? What is the SAT/ACT score recommended by each college/university? How much is the tution fees? Will the tution fee be different for the families with different household income? This ETL project extracts the data to answer all these questions.

### Extraction of data from the datasources
- List of colleges and universities dataset as csv file from Homeland Infrastructure Foundation-Level Data (HIFLD).
- College tution json data from api.data.gov
- Web scraping of top rated national universities in US
    
### Transformation
- Jupyter Notebook is used to read the csv and json files.
- From the csv file, the data regarding all the colleges were extracted and transformed into a dataframe.
- From the json file, relevant data regarding admission to all the colleges were loaded into dataframe and cleaned. 
- The dataset of top rated colleges were web scraped and transformed into pandas dataframe.
- String to numeric convertion was done by rermoving the comma.

### Loading
- Loaded the data tables into SQLite database

## Future development
- Create visualizations and perform analysis.
- Incoroporate machine learning to predict the college cost for the next 20 years.


## Requirement to run the program
- API Key - avilable in the link https://api.data.gov/signup/
- Google Chromedriver need to be installed and PATH need to be specified
- Enter the api key in the config file
