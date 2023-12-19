### data-collection-challenge
This is a two part program consisting of two jupyter notebook files, [part_1_mars_news.ipynb](part_1_mars_news.ipynb)
and [part_2_mars_weather.ipynb](part_2_mars_weather.ipynb).  

## Part 1 - Web Scraping
Part 1 scrapes the Mars news site, https://static.bc-edx.com/data/web/mars_news/index.html.  Using Beautiful Soup, it extracts text elements from the page and creates a Python dictionary list to store it in. 

## Part 2 - Analyzation
Part 2 Analyzes the data to answer the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    This is plotted as a bar chart. 
- Which months have the lowest and the highest atmospheric pressure on Mars?
ths on Mars (at the location of Curiosity)?
    This is plotted as a bar chart. 
- About how many terrestrial (Earth) days exist in a Martian year? (Calculated by by plotting the daily minimum temperature.)

Finally, the data is exported to a csv file named mars_data.csv.

Program written by Alana Castellano
Started code provided by Ariel Gamino 
