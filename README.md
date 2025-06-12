# Homework-7
Homework 7 for Lede Program

## Web Scraping exercises using Python

This repository contains exercises where I use Python to perform web scraping on [Wikipedia](https://en.wikipedia.org/wiki/List_of_presidents_of_the_United_States) and [Le Monde](https://www.lemonde.fr). BeautifulSoup and Pandas libraries were used for the scraping.

For the Le Monde exercise, the script collects every article’s title, subheader, URL, premium status, byline, article type, and image URL from the homepage.

## Auto-updating scraping

I also implemented an auto-updating code that scrapes Le Monde site every 5 hours and generates a new .csv output file.