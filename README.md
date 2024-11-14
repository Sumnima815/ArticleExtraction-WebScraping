The python project automates the extraction of news article from the Kathmandu Post website.
The script scrapes the homepage for article links, filters out irrelevant URLs and extracts essential contentsuch as heading, author, publication date, and body text. The extracted data is saved into CSV files for easy access and analysis.


## Introduction
This project demonstrates the process of web scraping by targeting a news website, Kathmandu Post. It extracts links from the homepage, filters social media URLs, and processes only valid news article URLs. The final extracted data, including headings, authors, publication dates, and content, is saved into a CSV file for further analysis.

##Features

Scrapes all article links from the homepage of Kathmandu Post.
Filters out social media and invalid URLs.
Extracts relevant content (heading, author, date, and body text) from each article.
Saves both the list of URLs and the extracted article data to CSV files.
Handles network errors and missing data gracefully.


## Usage 
1. Run the scraper:
   python 101.py

2. The scraper will:
   Fetch all links from the Kathmandu Post homepage.
   Filter out social media links.
   Extract the heading, author, publication date, and body content from valid articles.
   Save the links in data_links.csv and the extracted article content in kathmandu.csv.

   
3. CSV output :
   data_links.csv : Contains list of extracted links.
   kathmandu.csv : Contains extracted article data with fields such as heading, author, date      and content.

## Project Structure


101.py  :                 # Main script that runs the scraper
data_links.csv    :       # CSV file containing all extracted URLs
kathmandu.csv :           # CSV file containing article data
README.md    :            # Project documentation requirements.txt  
requirements.txt          # Python dependencies for the project

