# Web scraping ETL pipeline in Python

## Objective 
To create a ETL pipeline to scrap website, do some processing and finally load in a database of choice.

## Tools used
- Python
  - requests, request-html
  - beautifulsoup
  - concurrent
  - sqlite3
  - pandas
  - Pycharm IDE
- Multithreading
- OOPs
- SQL

## Design Architecture
We will create a ETL class that will encapsulate the ETL logic for a particular page.
Once we have the list of all such pages we shall use multithreading and scale up the ETL by creating an object of ETL class for each page and running the pipeline for each in multithreading. 

## Learnering from this exercise
- Web scraping and website inspecting
- Multithreading
- ETL building
- Creating Object Oriented Programs
- Creation of functools' partial functions
- Storing data into RDBMS

## Refereces
1. [NHAI list of Toll Plazas](https://tis.nhai.gov.in/tollplazasataglance.aspx?language=en#).
2. [NHAI Rate Page for a Plaza](https://tis.nhai.gov.in/TollInformation.aspx?TollPlazaID=99).
3. [functools' offical documentation](https://docs.python.org/3/library/functools.html#partial)
4. [concurrent module](https://docs.python.org/3/library/concurrent.futures.html)