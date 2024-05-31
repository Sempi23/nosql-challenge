# nosql-challenge
Module 12 Challenge

BACKGROUND

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.


REQUIREMENTS

1. Database and Jupyter Notebook Set Up
    - Creating Jupter Notebooks and using MOngoDB to extract data
2. Update the Database
    - Adding new data and deleting unwanted information.
    - Converting some data into appropriate forms.
3. Exploratory Analysis

    The following questions were answered by performing data queries and building an aggregate pipeline:

    a) Which establishments have a hygiene score equal to 20?

    b) Which establishments in London have a Rating Value greater than or equal to 4?

    c) What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new restaurant added (Penang Flavours)?

    d) How many establishments in each Local Authority have a hygiene score of zero, sorted from highest to lowest?




RREFERENCES


UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).