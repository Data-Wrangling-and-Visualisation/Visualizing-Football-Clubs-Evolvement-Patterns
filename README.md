# Visualizing Football Clubs and Players Evolvement Patterns
A Project for Data Wrangling and Visualization Course, Spring 2025. \
This project aims to extract and emphasize key trends in worldwide club and country football, considering multiple and diverse metrics to balance outcomes quite well. Some of the included metrics are: number of club players involved in national teams, transfer balance of clubs, average age of players within a club, etc. \
Team members: **Maksim Ilin, Rail Sabirov, Ivan Ilyichev**
- "analysis" folder contains separate folders for each metric named accordingly. \
 Each folder inside this folder contains two files: **.ipynb** for data processing and **.json** containing resulting data, which is ready for the visualization on a front end side.
- "web" folder contains two folders with files (data, scipt.js, styles.css, index.html) for two visualizations (Teams Scatter and World HeatMap).  These are only unpolished developments so far.
- "parsing" folder contains scrapy projects for parsing all data from transfermarkt. "parsedData" folder inside contains all parsed data, that was/will be analyzed and cleaned in "analysis".
- "json_to_postgresql" contains a Jupyter notebook that converts prepared cleaned json files (from the "analysis folder") into psql tables. The database server is hosted on an Innopolis University virtual machine.
- "app" contains Flask API.
