# Web-Scraping-Data-Handling-Challenge

## Description
This project scrapes movie and TV show data from JustWatch using Python libraries like Selenium, BeautifulSoup, and Pandas. The data includes information on movies and shows, such as titles, release years, genres, IMDb ratings, and available streaming platforms. After gathering the data, it is filtered and analyzed based on specific criteria and exported to a CSV file.

## Features
Web Scraping: Extracts movie and TV show information from JustWatch using BeautifulSoup.
Data Filtering: Includes only movies and shows released in the last two years with IMDb ratings of 7 or higher.
Data Analysis: Calculates average IMDb ratings, top genres, and the streaming platform with the most content.
Data Export: Saves filtered data to a CSV file for further use.

## Requirements
Python 3.x, 
Jupyter Notebook

## Required Libraries:

pip install bs4, 
pip install requests, 
pip install selenium, 
pip install pandas

## Project Structure

Web Scraping & Data Handling Challenge.ipynb: Jupyter notebook with detailed steps to scrape, filter, analyze, and export data.
Output CSV: Contains the filtered and analyzed data (generated during the project).

## Usage
Install Required Libraries: Ensure all dependencies are installed using the commands above.
Run the Notebook: Open Web Scraping & Data Handling Challenge.ipynb in Jupyter Notebook and execute cells in sequence.
Data Export: The final data is saved in CSV format, ready for further analysis.

## Data Details
### Movie Data:

Title, Release Year, Genre, IMDb Rating, Streaming Services, URL

### TV Show Data:
Title, Release Year, Genre, IMDb Rating, Streaming Services, URL

## Analysis Tasks

1. Filter by Recent Releases:
   Includes only movies and shows from the last two years.
3. IMDb Rating Threshold:
   Only items with an IMDb rating of 7 or higher are included.

5. Genre and Platform Analysis:
Average IMDb rating
Top 5 genres by content count
Platform with the highest number of offerings

## Submission
Colab Notebook: Ensured code is error-free and executable.
CSV Data File: Make accessible via a shared link.
