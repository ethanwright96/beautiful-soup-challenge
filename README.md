beautiful-soup-challenge
# Web Scraping and Data Analysis

This is a GitHub repository for the homework assignment on web scraping and data analysis. The assignment consists of two parts, each with its own set of tasks and deliverables.

## Part 1: Scrape Titles and Preview Text from Mars News

In this part, you will scrape the titles and preview text from Mars news articles. Follow the steps below:

1. Open the Jupyter Notebook named `part_1_mars_news.ipynb` in the starter code folder.
2. Use automated browsing techniques to visit the Mars News website and inspect the page to identify the elements to scrape.
3. Create a Beautiful Soup object and extract the text elements from the website.
4. Store the scraped titles and preview text in Python data structures. Each pair should be stored as a dictionary with two keys: 'title' and 'preview'.
5. Store all the dictionaries in a Python list.
6. Print the list in your notebook.
7. Optionally, you can export the scraped data to a JSON file for easier sharing.

## Part 2: Scrape and Analyze Mars Weather Data

In this part, you will scrape and analyze Mars weather data. Follow the steps below:

1. Open the Jupyter Notebook named `part_2_mars_weather.ipynb` in the starter code folder.
2. Use automated browsing techniques to visit the Mars Temperature Data Site and inspect the page to identify the elements to scrape. The URL for this site is `https://static.bc-edx.com/data/web/mars_facts/temperature.html`.
3. Create a Beautiful Soup object and scrape the data in the HTML table. You can also use the Pandas `read_html` function if you prefer.
4. Assemble the scraped data into a Pandas DataFrame with the appropriate column headings.
5. Examine the data types associated with each column and convert them to the appropriate datetime, int, or float data types if necessary.
6. Use Pandas functions to analyze the dataset and answer the following questions:
   - How many months exist on Mars?
   - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
   - What are the coldest and warmest months on Mars (at the location of Curiosity)? Find the average minimum daily temperature for all the months and plot the results as a bar chart.
   - Which months have the lowest and highest atmospheric pressure on Mars? Find the average daily atmospheric pressure of all the months and plot the results as a bar chart.
   - About how many terrestrial (Earth) days exist in a Martian year? Visualize the daily minimum temperature and estimate the result.
7. Export the DataFrame to a CSV file.
