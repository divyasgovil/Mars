# Mars
This project consists of two technical products.
Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
# Part 1: Scrape Titles and Preview Text from Mars News
1. Open the Jupyter Notebook in the starter code folder to scrape the Mars News website.
Use automated browsing to visit the Mars news siteLinks to an external site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to extract text elements from the website.

3. Extract the titles and preview text of the news articles scraped. Store the scraping results in Python data structures

# Part 2: 
1. Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb to scrape and analyze Mars weather data.

2. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site. Inspect the page to identify which elements to scrape.

3. Create a Beautiful Soup object and use it to scrape the data in the HTML table. 

4. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location

5. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

6. Analyze dataset by using Pandas functions to answer the following questions:

a) How many months exist on Mars?
b) How many Martian (and not Earth) days worth of data exist in the scraped dataset?
c) What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
d) Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
e) Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
f) About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

7. Export the DataFrame to a CSV file.
