
An analysis of Social Buzz's content categories that highlights the top 5 categories with the largest aggregate popularity.

Task Overview
- Identify which datasets will be required to answer the client’s business question
- Clean the datasets and merge them to prepare the data for analysis
- Determine the answer to the client’s business question.
The client has sent through:

follow these steps:
1. Requirements gathering
2. Data cleaning
3. Data modelling

Requirements gathering:
source:(https://www.theforage.com/simulations/accenture-nam/data-analytics-mmlb)

Data Cleaning:
- removing rows that have values which are missing:
1. Filter the data each column
2. From filtering process in column type(it is because the value will be important so need to delete all missing rows in this column) click blank then delete all sheet blank rows
3. Then unclick blank in filter to show cleaned data

-changing the data type of some values within a column, and
removing columns which are not relevant to this task.
1. Delete URL and USER ID column because it have represented by content ID 
2. Create new column sentiment and scores which its values is based on reactiontypes.csv using vlookup formula.
3. check spelling data string.
4. delete all quotation mark.
5. lowering case all data content type to make it same.
6.Delete All USER ID(karena fokus permasalahannya ada pada popular content)

Data modelling:
1. using pivot table function to get summary value from correlation each column or variable that we want
2. Then use pivot function to show which content have big score the most and make into pivot table 
3. Last use that table for make a histogram and pie chart
