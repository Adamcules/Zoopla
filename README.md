# Zoopla_Webscrape

This file performs a simple webscrape of the Zoopla website. 
It first opens a URL that is a search result page for properties in London (URL is fixed), and asks the user how many pages they would like to scrape.

The code gets the hyperlinks for each listed property and adds them to a list (big_link_list) and then closes the browser.

The code then iterates through this list and opens each link in turn.
For each property page visited in this way, the price and address is got and added to a list (info_list).

Finally the info list is printed.
