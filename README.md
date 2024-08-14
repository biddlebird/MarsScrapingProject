# Mars Scraping and Data Analysis Project

## Background

In this project, I applied web scraping and data analysis techniques to collect, organize, and analyze data from Mars-related websites. The goal was to strengthen skills in data collection, organization, analysis, and visualization. I used tools such as Splinter and Beautiful Soup for scraping web data and Pandas for data analysis.

## What I Created

This project consists of two main deliverables:

### Deliverable 1: Scrape Titles and Preview Text from Mars News Articles

1. **Jupyter Notebook**: `part_1_mars_news.ipynb`
2. **Steps Taken**:
   - Used automated browsing with Splinter to access the Mars news website.
   - Inspected the HTML elements to identify the relevant data for scraping.
   - Created a Beautiful Soup object to parse the HTML and extract news article titles and preview text.
   - Stored each title-and-preview pair in a Python dictionary and collected all dictionaries in a list.
   - Printed the list in the notebook.
   - Optionally exported the data to a JSON file for ease of sharing.

### Deliverable 2: Scrape and Analyze Mars Weather Data

1. **Jupyter Notebook**: `part_2_mars_weather.ipynb`
2. **Steps Taken**:
   - Used automated browsing with Splinter to visit the Mars Temperature Data site.
   - Created a Beautiful Soup object to scrape data from the HTML table.
   - Assembled the scraped data into a Pandas DataFrame with columns matching the table headings:
     - `id`: Identification number of a transmission from the Curiosity rover
     - `terrestrial_date`: Date on Earth
     - `sol`: Number of elapsed sols (Martian days)
     - `ls`: Solar longitude
     - `month`: Martian month
     - `min_temp`: Minimum temperature (Celsius) of a Martian day
     - `pressure`: Atmospheric pressure at Curiosity's location
   - Examined and converted data types as needed.
   - Analyzed the dataset to answer the following questions:
     1. **Number of Martian Months**: Calculated the number of distinct Martian months.
     2. **Total Martian Days**: Counted the total number of Martian days in the dataset.
     3. **Coldest and Warmest Months**:
        - Calculated average minimum daily temperatures for each month.
        - Plotted the results as a bar chart.
     4. **Months with Lowest and Highest Pressure**:
        - Calculated average daily atmospheric pressure for each month.
        - Plotted the results as a bar chart.
     5. **Martian Year Duration**:
        - Estimated the number of terrestrial days in a Martian year by analyzing the daily minimum temperature plot.
   - Exported the DataFrame to a CSV file for further use.

## Files

- **`part_1_mars_news.ipynb`**: Jupyter notebook for scraping Mars news titles and previews.
- **`part_2_mars_weather.ipynb`**: Jupyter notebook for scraping and analyzing Mars weather data.
- **`mars_data.csv`**: CSV file containing the scraped Mars weather data (exported).

## Tools and Libraries Used

- **Splinter**: For automated browsing and interaction with web pages.
- **Beautiful Soup**: For parsing HTML and extracting data.
- **Pandas**: For data analysis and manipulation.
- **Matplotlib**: For plotting charts and visualizing data.

---

This README provides a clear overview of what was accomplished in the project, including details on the process and deliverables.
