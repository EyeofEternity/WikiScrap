# Wikipedia Data Scraping

Just a small project of webscrapping using python for **ES112 : Computing**. Probably very naive. Feel free to contribute.

The first, `incidents.py` finds the aviation incidents in the given year. The second (`fatality.py`), takes two inputs, the first being the number `n` of the top `n` most fatal incidents that occured and the second determines the incdents that occured in the last `y` years.

The data required to be loaded in second file takes about an hour. So, a copy of the data is given in `temp.txt`. Delete it to re-download the data. The data download is throttled to avoid loading Wikipedia.

# Requirements:
Python 3 with `requests` and `BeautifulSoup4`.

[Wikipedia data](https://en.wikipedia.org/wiki/List_of_accidents_and_incidents_involving_commercial_aircraft) and other links on that page.
