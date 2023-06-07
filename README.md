# Mars Web Scraping and Data Analysis
## Background
Throughout this project, I have developed and strengthened my web scraping and data analysis skills. I have learned how to identify HTML elements, extract information from webpages using automated browsing with Splinter and HTML parsing with Beautiful Soup, and scrape various types of data such as tables and recurring elements. These skills have enabled me to collect, organize, analyze, and visualize data effectively.

## What I've Created
This assignment consists of two technical products that I have successfully completed:

## Deliverable 1: Scrape Titles and Preview Text from Mars News
To accomplish this deliverable, I followed the steps outlined in the Jupyter Notebook "part_1_mars_news.ipynb" provided in the starter code folder. Here's what I did:

1. Utilized automated browsing to visit the Mars News website and inspected the page to identify the elements to scrape.
2. Created a Beautiful Soup object and extracted the titles and preview text of the news articles from the website.
3. Stored the scraping results in Python data structures, specifically a list of dictionaries. Each dictionary contains two keys: "title" and "preview", with corresponding values for each news article.
4. Printed the list of dictionaries in the notebook.
5. Exported the scraped data to a JSON file for easier sharing.

## Deliverable 2: Scrape and Analyze Mars Weather Data
For this deliverable, I followed the steps outlined in the Jupyter Notebook "part_2_mars_weather.ipynb" provided in the starter code folder. Here's what I accomplished:

1. Used automated browsing to visit the Mars Temperature Data Site, which is available at https://static.bc-edx.com/data/web/mars_facts/temperature.html. I inspected the page to identify the elements to scrape.
2. Created a Beautiful Soup object and scraped the data from the HTML table on the website. I assembled the scraped data into a Pandas DataFrame, ensuring that the column headings matched those in the table.
3. Examined the data types associated with each column in the DataFrame and performed any necessary data type conversions (casting).
4. Analyzed the dataset using various Pandas functions to answer the following questions:
* How many months exist on Mars?
* How many Martian days (sols) worth of data are available in the scraped dataset?
* What are the coldest and warmest months on Mars at the location of the Curiosity rover? To answer this, I found the average minimum daily temperature for each month and plotted the results as a bar chart.
* Which months have the lowest and highest atmospheric pressure on Mars? I found the average daily atmospheric pressure for each month and plotted the results as a bar chart.
* Approximately how many terrestrial (Earth) days exist in a Martian year? To estimate this, I plotted the daily minimum temperature and considered the time it takes for Mars to complete one orbit around the Sun.
5. Exported the DataFrame to a CSV file for further analysis or sharing.
