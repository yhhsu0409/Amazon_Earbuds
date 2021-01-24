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
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Data_Table.png" width="650" height="300">

## Analysis (PowerBI)
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0001.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0002.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0003.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0004.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0005.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0006.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0007.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0008.jpg" width="1000" height="600">
<img src="https://github.com/yhhsu0409/Amazon_Earbuds/blob/master/ReadMe_Pic/Pdf_to_Jpg/Amazon_BI_PDF_page-0009.jpg" width="1000" height="600">

## References
* 洪錦魁 . (2019). Python網路爬蟲：大數據擷取、清洗、儲存與分析：王者歸來. 台灣: 深智數位出版社 
* 數據分析那些事 . “一次讓人臉紅心跳的python數據分析.” Medium, 6 Oct. 2019, allaboutdataanalysis.medium.com/%E4%B8%80%E6%AC%A1%E8%AE%93%E4%BA%BA%E8%87%89%E7%B4%85%E5%BF%83%E8%B7%B3%E7%9A%84python%E6%95%B8%E6%93%9A%E5%88%86%E6%9E%90-ab5c2e41fea0. 
