# PostgreSQL analysis of International Rugby Union results  

Data analysis is taking more and more importance in sports to extract useful informations. This outcomes could be of particular interest not only for sport (for example, coaches who are interested in team's or player's performance) but also for business (number of sold tickets, etc.).

This notebook presents a short analysis of a dataset built on results of international rugby teams from 1871 to 2023 using PostgreSQL. Data visualization is done with Seaborn.

**Dataset**

<u>URL:</u> https://www.kaggle.com/datasets/lylebegbie/international-rugby-union-results-from-18712022

This dataset is available on Kaggle. It consists of one CSV file:
 - *results.csv*: date, home/away away teams and results, stadium, etc.

**Roadmap**
1. Importing data from CSV files
2. Answering questions:
    - How many teams are present in the dataset?
    - How many matches were played in the different countries?
    - What is the home win percentage?
    - Which team has the best home/away win ratio?
    - Which team has the best win/loss ratio since 1871?
    - Which team has the best win/loss ratio during 6 Nations?
    - Which team has the best win/loss ratio at a neutral venue?
    - What is the largest score difference during a win of the French team?
    - Which team has the largest average of points scored during a match?
    - What are the favorite country and city to play matches?
    - Which country has the largest number of stadiums?

**Tools**
- PostgreSQL: Analysis
- Python: 
    - ipython-sql: SQL in Jupyter notebook
    - Pandas, Seaborn: Data visualization
