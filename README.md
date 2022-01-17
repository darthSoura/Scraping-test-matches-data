# Scraping-test-matches-data
This is a Web scraping project using BeautifulSoup and Python to scrape basic information of all the Test matches played till Jan 2022. 

To see the code, open the test-match-records.ipynb file.

The data is scraped from the ESPNCricinfo Stats website using BeautifulSoup and rendered into a CSV file using Pandas.<br>
Link to the Source page: https://stats.espncricinfo.com/ci/content/records/307847.html 

The data is initially arranged year-wise. Using web scraping, first the links to individual years are extracted a and then web scraping is performed on those links to get the data of all Test Matches.

From the scraped Year links, the By_Year folder is created, containing CSV files for each years' matches. Then the CSV files are read and a master CSV file containing all the matches is created and stored as All_Matches.csv.

Then the All_Matches.csv file is used to segregate the data into other folders like By_Ground, By_Team and By_Hosting_Nation.

You may find some anomalies in the CSV files in the Host Team column. Those anomalies are explained in the Jupyter Notebook.

The above dataset is also uploaded to Kaggle: https://www.kaggle.com/bong952/test-matches-played-from-1877-jan-2022 <br>
The Jupyter notebook was originally posted and edited on Jovian: https://jovian.ai/ash007online/test-match-records

This is my first Web Scraping project. Kindly give a Star if you like it !!!
