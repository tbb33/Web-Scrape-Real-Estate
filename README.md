# Web-Scrape-Real-Estate

## This script will scrape a website for properties listed for sale.

HTML elements are the key to web scraping. 

This script:
1. web scrapes century21.com
2. python performs search query on location 
3. stores data in tbl (pandas df)
   - Gets data wtih 1 run of the program. Saves output in csv file (with columns: address, area, beds, full baths, locality, lot size, price)
<br>

Basic Web Scraping Logic: 
1. load entire html script in py using request lib (gives url)
2. Use beautiful soup library to extract elements
3. store extracted text in vars/dict/pandas df
