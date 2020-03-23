# Webscraping
This is the web scraping project which scrape iPad4 information on eBay.

Steps:

1. Visit the website, use request and beautiful soup package, get all the content on the web pages and save them in html files. 

2. Identify the sponsored and non-sponsored items on each page, select their urls and save them in a txt file. Then save them one by one as txt files. The name of the file is the item id. The url is in the txt file. All the txt files are stored in two folders.

3. Define functions to get different information on the web pages. Information includes sellers' name, price, delivery option, the rating score, etc.

4. Loop all the urls in the folders, visit them, get all the needed information by using functions defined in 3, and store in a txt file. use writer.writerow(), sperate each element with ','.

5. Connect to the MySQL database, create a table and define all the data types. Define a function to import data from csv file to MySQL table.
