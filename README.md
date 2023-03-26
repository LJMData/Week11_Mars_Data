# Week11_Mars_Data

This code is designed to scrape titles and preview text from the Mars news website, store the results in Python data structures, and print the list of dictionaries in the notebook. Here is a breakdown of the code:

Part 1: Scrape Titles and Preview Text from Mars News

Step 1: Visit the Website
Using automated browsing, the code visits the Mars news site and inspects the page to identify which elements to scrape.

Step 2: Scrape the Website
The code sends an HTTP GET request to the website and retrieves the HTML content of the page. It then creates a Beautiful Soup object and extracts all the text elements from the HTML. The text elements are printed to the console to confirm success.

Step 3: Store the Results
The code extracts the titles and preview text of the news articles that were scraped. It stores each title-and-preview pair in a Python dictionary and gives each dictionary two keys: title and preview. The dictionaries are then stored in a Python list. The list is printed to the console to confirm success.

The code then closes the automated browsing session.

Part 2: Scrape Temperature data from Mars data Stations. 

Step 1: Visit the Website
Using automated browsing, the code visits the Mars news site and inspects the page to identify which elements to scrape.

Step 2: Scrape the Website
The code sends an HTTP GET request to the website and retrieves the HTML content of the page. It then creates a Beautiful Soup object and extracts all the text elements from the HTML. The text elements are printed to the console to confirm success.

Step 3: Data Storage
The code extracts each row of the table and stores it into a Python Dictionary under the appropriate headings. This data is then converted into a Pandas DataFrame.

Step 4: Data Analysis
The data is converted into the appropriate format for each column and queried to find averages, among other statistics. Visualization techniques support these results. The raw data is exported to a CSV.