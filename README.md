# Web-Scraping Mars Data

Identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup

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

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/6508ca9c-3cda-45c0-9b00-3c6cded96fd4)

Assembled the scraped data into a Pandas DataFrame.

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/99977ef5-bbd8-4501-97d2-3395aa42e167)

Prepare Data for Analysis: 

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/f06a1ab3-a8af-41d4-81d8-1027edc75ca6)

Analysis of Mars Data:
The following questions were answered: 

How many months exist on Mars?

How many Martian (and not Earth) days worth of data exist in the scraped dataset? 
![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/c29cb344-2466-459f-a055-6aa8d9060431)

What are the coldest and the warmest months on Mars (at the location of Curiosity)?  

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/a61cb15f-8afe-4e74-b633-4da6036e9474)
![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/b98fe1cb-0e0c-48c3-80b7-f903cfd4a706)



Which months have the lowest and the highest atmospheric pressure on Mars?  
![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/0372f38a-c928-48cb-b9e7-08af5071afaf)

About how many terrestrial (Earth) days exist in a Martian year? 
Visually estimated the results by plotting the daily minimum temperature. 

![image](https://github.com/albertdudek7/Mars_Web_Scraping/assets/127783844/d134fb6f-68dc-4aec-94c4-9def9e5e4913)



