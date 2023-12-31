# Mars-Weather-News
YK UofT Data Analytics Mars-Challenge  

**"A full web-scraping and data analysis project. HTML elements identified on a page, with their id and class attributes, and information extracted via both automated browsing with Splinter and HTML parsing with Beautiful Soup as well as various types of information that include HTML tables and recurring elements, like multiple news articles on a webpage."**

![image](https://github.com/YargKlnc/Mars-Weather-News/assets/142269763/0cdf26a8-2bc0-40ef-8e42-91632211bb65)

This work consists of two parts: 

** Part 1: Scraping titles and preview text from Mars news articles

** Part 2: Scraping and analysis of Mars weather data

======================================================================

**Part 1: Scraping Titles and Preview Text from Mars News:**

- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup)

- The titles and preview text of the news articles were scraped and extracted

- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries

======================================================================

**Part 2: Scraping and Analysis of Mars Weather Data**

- The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types

- The data was analyzed to answer the following questions: 

  * How many months exist on Mars? 
  * How many Martian days worth of data are there?
  * The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 

    * Which month, on average, has the lowest temperature? The highest? 
    * Which month, on average, has the lowest atmospheric pressure? The highest? 
    * How many terrestrial days exist in a Martian year? A visual estimate within 25% was made
  
- The DataFrame was exported into a CSV file

  
**References**

Mars photo and all rights belongs to www.downtoearth.org.in. https://www.downtoearth.org.in/news/science-technology/what-caused-mars-to-dry-out-a-new-study-provides-clues-83040
