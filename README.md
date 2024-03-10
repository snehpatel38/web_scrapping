# Ahmedabad Cafe Web Scraper

This Python script uses Selenium and BeautifulSoup to scrape cafe information from Zomato for restaurants in Ahmedabad. The script scrolls through the webpage to load all the content dynamically and extracts details such as name, rating, cuisine, rate, and link for each cafe.

## Requirements

- Python 3.x
- Selenium
- BeautifulSoup
- Pandas

## Installation

1. Install Python 3.x from [python.org](https://www.python.org/downloads/)
2. Install required libraries using pip:
   ```bash
   pip install selenium beautifulsoup4 pandas

## Usage 

1. Update the city variable in the script to the desired city (e.g., "ahmedabad").
2. Run the script using the command:
   bash
   ```bash
   python zomato_scraper.py
3. The script will start scraping the cafe information and save it to a CSV file named zomato_ahmedabad.csv.

## Note

1. Adjust the scrolling speed (time.sleep(2)) based on your network speed and content loading speed.
2. Modify the script as needed for other cities or categories on Zomato.