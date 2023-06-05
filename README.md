# web_scraping
Part 1: Scrape Titles and Preview Text from Mars News
1.Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape
2.Create a Beautiful Soup object and use it to extract text elements from the website.
3.Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
4.Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
5.Print the list in your notebook.


Part 2: Scrape and Analyse Mars Weather Data
1.Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyse Mars weather data.
2.Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
3.Assemble the scraped data into a Pandas DataFrame. 
4.Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

Answer the following questions:
1.How many months exist on Mars?
2.How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3.What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
4.Find the average minimum daily temperature for all of the months.
5.Plot the results as a bar chart.
6.Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
7.Find the average daily atmospheric pressure of all the months.
8.Plot the results as a bar chart.
9.About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
10.Consider how many days elapse on Earth in the time that Mars circles the Sun once.
11.Visually estimate the result by plotting the daily minimum temperature.
12.Export the DataFrame to a CSV file.
