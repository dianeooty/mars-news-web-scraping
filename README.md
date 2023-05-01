# mars-news-web-scraping
> T I utilized web scraping to parse the Mars News data and complete data analyses for the Mars News Articles and Mars Weather Data sites.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
For Part 1 of the challenge, web scraping was completed using Splinter and BeautifulSoup for the Mars News Site. The titles and previews for each article was extracted, stored as a Python dictionary and then exported as a JSON file.

For Part 2 fo the challenge, automated browsing was used to scrape the data from the Mars Weather Site.  The table's header and rows were extracted into Python objects and then converted to a DataFrame using Pandas.  Data analysis was completed from the DataFrame, comparing Martian to Terrestrial days/months/years using Pandas plot to reflect the average minimum temperatures and average pressures as a visual guide to answering the challenge questions.


## Technologies Used
- HTML
- BeautifulSoup
- Splinter
- JSON
- Python
- Pandas
- Jupyter Notebook


## Screenshots
![1](https://user-images.githubusercontent.com/117790100/221794349-2e7a726a-11c0-4a1e-9bcb-c6e6f5f4de74.png)
![2](https://user-images.githubusercontent.com/117790100/221794350-0ff4ea7d-c3e4-409e-97cc-831f370a1580.png)
![3](https://user-images.githubusercontent.com/117790100/221794352-394bb982-56a3-4c4e-aba5-9ee3511d3ac9.png)
![4](https://user-images.githubusercontent.com/117790100/221794353-1a4d965c-f516-4cd5-8da4-6284666e14a9.png)


## Setup
The Mars Weather Data in csv format and the Mars News Artical in JSON format can be found in the output_data folder.  The following urls were used for this challenge:
https://static.bc-edx.com/data/web/mars_news/index.html
https://static.bc-edx.com/data/web/mars_facts/temperature.html


## Project Status
Project is complete and no longer being worked on.


## Acknowledgements
- Many thanks to my instructional staff and David Chao.


## Contact
Created by Diane Guzman


