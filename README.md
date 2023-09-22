# Web-Scraping Mars Data

Identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Part 1: Scrape Titles and Preview Text from Mars News

Using automated browsing to visit Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape. 

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/c88bfa4a-7afc-46b1-a67a-a85e3d8998ea)

Extract the titles and preview text of the news articles.

Stored each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview.

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/9f0c5e49-3553-449a-b605-bb693e1c2b93)

Part 2: Scrape and Analyze Mars Weather Data

Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspected the page to identify which elements to scrape. 

Assembled the scraped data into a Pandas DataFrame.

HINT Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars? How many Martian (and not Earth) days worth of data exist in the scraped dataset? What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question: Find the average minimum daily temperature for all of the months. Plot the results as a bar chart. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question: Find the average daily atmospheric pressure of all the months. Plot the results as a bar chart. About how many terrestrial (Earth) days exist in a Martian year? To answer this question: Consider how many days elapse on Earth in the time that Mars circles the Sun once. Visually estimate the result by plotting the daily minimum temperature. Export the DataFrame to a CSV file.
