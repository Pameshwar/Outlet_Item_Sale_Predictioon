# The reasons of going wtih pytrends
pytreds is python library for google Trend Searach. As Python is dianamic language and it has a large community supports. This library provides proxy 
servers in case we reached google date rate limit. We customise request parameters for connection and search options, that is the main reason to choose this library. 

The following API methods are available seraching trends:

Interest Over Time: returns historical, indexed data for when the keyword was searched most as shown on Google Trends' Interest Over Time section.
Historical Hourly Interest: returns historical, indexed, hourly data for when the keyword was searched most as shown on Google Trends' Interest Over Time section. It sends multiple requests to Google, each retrieving one week of hourly data. It seems like this would be the only way to get historical, hourly data.
Interest by Region: returns data for where the keyword is most searched as shown on Google Trends' Interest by Region section.
Related Topics: returns data for the related keywords to a provided keyword shown on Google Trends' Related Topics section.
Related Queries: returns data for the related keywords to a provided keyword shown on Google Trends' Related Queries section.
Trending Searches: returns data for latest trending searches shown on Google Trends' Trending Searches section.
Top Charts: returns the data for a given topic shown in Google Trends' Top Charts section.
Suggestions: returns a list of additional suggested keywords that can be used to refine a trend search.
  

# How to Intall and execute your program
Steps:
  1. Make Sure you have installed python version > 3.3
  2. pip install requiremts.txt
  3. Run : python trends.py
