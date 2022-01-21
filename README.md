# Web-Scrape-Real-Estate

## This script will scrape a website for properties listed for sale.


The script final_century21.ipynb:
1. web scrapes century21.com and gets info from multiple pages from the site
2. python performs search query on location 
3. stores data in tbl (pandas df)
   - Gets data wtih 1 run of the program. Saves output in csv file (with columns: address, area, beds, full baths, locality, lot size, price)
<br>

HTML elements are the key to web scraping. 

Basic Web Scraping Logic: 
1. load entire html script in py using request lib (gives url)
2. Use beautiful soup library to extract elements
3. store extracted text in vars/dict/pandas df

<br>

Other files:
1. PropertyListings.csv - example of the output from final_century21.ipynb
2. century21.ipynb - shows my logical steps in building the final script. Shows how to extract info from the first page only.
3. example_web_scrape_cities.ipynb - shows my first time working on web scraping with a simple example. 
