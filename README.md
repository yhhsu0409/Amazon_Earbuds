# Amazon_Earbuds
There are many earbuds brands in the market and each brands have different products.
Therefore, this project will be interested on each brand's advantages and disadvantages, such that customers can have an idea on picking the desire earbuds.
The data of the brands will be crawl from Amazon and anlyze through price, ratings, reviews,...

## Data Crawling (Selenium + BeautifulSoup)
* Amazon_Data_Crawling.ipynb
Step 1) Crawl the headphone manufacturers from Wikipedia
* Gather the manufactuerers from Wikipedia
* Clean the name so make it searchable on Amazon (e.g. Sony Brand -> Sony)

Step 2) Change Amzaon to English Interface and Search for available brands
* Get ['Sony', 'Koss', 'Pioneer', 'SAMSUNG', 'Panasonic', 'JLAB', 'Beats', 'PIONEER', 'Jabra', 'Sennheiser', 'PHILIPS', 'Bang', 'Audio-Technica', 'Skullcandy', 'Shure', 'JVC', 'Plantronics', 'JBL', 'Monster']

Step 3) Crawl Available Items' Url from the brand
* Get 1494 urls (1494 items)

Step 4) Crawl Each Item's Information
* Titles, brands, prices, stars, number_ratings, review_words
img src="https://Data Table" width="400" height="300">

## Analysis (PowerBI)
PDF_Images
