For this project, I used webscraping to extract information regarding weather on Mars, then cleaned, visualized, and analyzed data using Python. 

This project was completed using the following workflow:

Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Scrape the Mars News (Links to an external site.) website by using Splinter and Beautiful Soup. Specifically, scrape the title and preview text, or summary text, of each article on the landing page.

Store all the dictionaries in a Python list.

Print the list in your notebook.

Optionally, store the scraped data in a file or database (to ease sharing the data with others). To do so, export the scraped data to either a JSON file or a MongoDB database.

The URL to find Mars Temperature Data is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.

Scrape the data in the HTML table. 

The id heading: The identification number of a single transmission from the Curiosity rover.
The terrestrial_date heading: The date on Earth.
The sol heading: The number of elapsed sols (Martian days) since Curiosity landed on Mars.
The ls heading: The solar longitude.
The month heading: The Martian month.
The min_temp heading: The minimum temperature, in Celsius, of a single Martian day (sol).
The pressure heading: The atmospheric pressure at Curiosity's location.
Examine the data types of all the DataFrame columns. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.


The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 

How many Martian (and not Earth) days worth of data exist in the scraped dataset?

What are the coldest and the warmest months on Mars (at the location of Curiosity)? Get the answer by averaging the minimum daily temperature of all the months. 

Which months have the lowest and the highest atmospheric pressure on Mars? Get the answer by averaging the daily atmospheric pressure of all the months. 

About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth? Visually estimate the result by plotting the daily minimum temperature.

How many months exist on Mars?

Which month, on average, has the lowest temperature? The highest?

Which month, on average, has the lowest atmospheric pressure? The highest?

How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.


**Methods used:**

Python

JSON 

MongoDB

Beautiful Soup

Splinter

Matplotlib

Pandas

Jupyter Notebook

