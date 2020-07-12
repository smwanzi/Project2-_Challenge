# project2-challenge

Coding Approach:
We chose a relational DBMS , Postgres as our Database because the data was mainly read in as tables (CSVs , JSONs- geoJSON and topoJSON) , and thus it was easier to pre-define schema ; Postgres seemed best fit.
Python’s Pandas was used to clean the dataset .
HTML and CSS’s Bootstrap were used to create and layout the webpage
Javascript library D3 was used to map the data and create dashboards.
ALso, D3-geomap library was used for creating geographic map.
A flask app in Python was used to serve the webpages
And finally it was deployed on Github.
Visualizations :
The Dashboard has a total of 3 Visualizations ,
A Choropleth map showing suicide deaths per 100,000 people across 198 countries . A tool tip details a line chart of suicide deaths per 100,000 people from the year 1950 - 2017.

An interactive Bar chart on the bottom left where you see suicide rates broken down by age group. Use the dropdown menu to make a country selection. These rates are given as the number of suicide deaths per 100,000 people in a given demographic.

Another Interactive bar chart on the bottom right that compares suicide rates in men (shown on the y-axis) versus rates in women (shown on the x-axis). These rates are also given as the number of suicide deaths per 100,000 people in a given demographic.