# merge_data_project
*Showcasing some techniques to merge and interact with data using Python's Pandas library.*

**Purpose**: The goal of this project was to practice some of the techniques I've been using at work. I designed this project to make the data and process very similar. 

The primary file for this project is 'merge_data.ipynb'. This contains all of the key techniques I wanted to highlight in this project.  

## Just a few notes before I describe the project more in depth:

 - All of this data is FAKE DATA. I downloaded it from a source linked below and altered it to make it look more similar to actual records.
 
 - The spirit of this project is to mimic large-scale data manipulation. 

This project's datasets are much smaller than the ones they are intended to mimic--at work, one company list contained 20,000 company records and some contact lists were as large as 1,500 (This project deals with 100 companies with 5 contacts per company). Any operations that may seem a little overkill are done because they were appropriate with these larger data sets. 

 - There is also a 'making_new_data' folder which contains the starter data 'us-500.csv' and 'making_new_data.ipynb'--I used this file to alter the starter data and create the 2 other data sets you see ('new_exported_contacts.csv' and 'company_data.csv'). These two datasets are the ones used in the main file merge_data.


## Here's the outline for the project:

- I've imported some fake data and altered it in the 'making_new_data' folder. In 'making_new_data.ipynb', I made two semi-realistic datasets: one with fake company info and another with fake contact info. For each dataset, company_url and company_name were altered to mimic discrepancies between two data sources.

- In the 'merge_data' file I imported those 2 datasets, cleaned them, and merged them together. In the end, we have a complete data set of contacts and their company info represented in the 'finished_contact_records.csv' file.

**Overall**, this process shows some of the trouble that comes with merging datasets that don't have a column of data in common. 

If you made it down all the way this far, thank you for taking the time to learn about my project--please feel free to poke around and look at the code.

[source to the fake data](https://www.briandunning.com/sample-data/)
