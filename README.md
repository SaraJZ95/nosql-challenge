
NoSQL Challenge

This project analyzes UK restaurant ratings from the Food Standards Agency. I imported the data from establishments.json into MongoDB using the command:

mongoimport --db uk_food --collection establishments --file establishments.json --jsonArray


The analysis is divided into two Jupyter notebooks: one for data import and updates, and the other for exploratory queries.


References

UK Food Standards Agency Links to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB Links to an external site.. Contains public sector information licensed under the Open Government Licence v3.0 Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).


Sara Joulaei/ Sep 18 - 2024
