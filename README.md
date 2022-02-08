# DU POC for BAs and DEs

## Feb 18th, 2022. Presentations will occur on this day 

You will be working in teams of two, with each team consisting of 1 BA and 1 DE.  __You will be working with whomever is on your capstone project!__

Each team will select a dataset available on www.kaggle.com to work with for the POC.

You will be modeling this data, profiling it, loading it into an RBDMS and preparing at least two visualizations.

## Requirements

You will need to work in your team of 2 people to complete the following:

1. __Model your dataset in Lucidchart__: Create a conceptual model for the data in Lucidchart. Your model must include entities, identifiers, and cardinalities. 
Your may use any modeling notation you’d like. _NOTE_: Many of the datasets in Kaggle are flat; that is, they consist of one big file.  Your model should 
consist of at least two tables.  In other words, you will be modeling the entities and relationships present in the dataset rather than the physical 
form of the dataset as it exists in Kaggle.

2. __Profile the data and assess its quality__: Profile the data in _at least one_ table.  That is, for each column present establish -- at a minimum -- the data type, minimum and maximum values (if applicable), null incidence,
and top 3-5 values (if appicable).  Be prepared to show how you profiled this data, as well as an assessment of the data quality based on the profiling results.

3. __Create the DDL for implementing your model in an RDBMS and execute it.__: Define each table using DDL and execute that DDL to build the tables in a RBDMS.

4. __Load your data__: Load the data from Kaggle into your RBDMS using psycopg2 or another module.

5. __Prepare data visualizations__: Prepare at least 2 visualizations in Python, Tableau or another tool. Be prepared to discuss why you chose a particular visualization strategy for each.


## Deliverables

The final deliverables for the POC should be available in a github repo for your team.  That repo should include:

1. A high-level summary of your POC in the readme.md file.

2. The data profiling and quality assessment, displayed in a table format in the readme.md file.

3. The data model for the data exported from LucidChart. 

4. The DDL used to create your tables in the RBDMS.

5. A py/ipynb file with the code used to transform and load the data into the RDBMS.

6. The code used to produce your visualizations (if applicable).

7. Your deck.


### Guidelines for your Code:

- You should be showcasing things you have learned throughout DU.
- Try to use more functions in python and less of a scripting mentality.
- Make sure your code and the steps you have taken to load your data into the database are clearly outlined
- Use a common Github repository for your team
