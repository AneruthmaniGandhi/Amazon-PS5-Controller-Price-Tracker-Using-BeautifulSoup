# Amazon-Webscraping

Amazon PS5 Controller Price Tracker

This Python script is designed to track the price of the PlayStation 5 DualSense Wireless Controller on Amazon. It periodically checks the product page, extracts the current price, and saves the data to a CSV file for further analysis.

Features:

Web Scraping: Utilizes BeautifulSoup to extract the title and price of the PS5 controller from Amazon's product page.
Data Storage: Saves the extracted information (title, price, and date) in a CSV file (AmazonWebScraperDataset.csv).
Price Alerts: Optionally, it can send an email notification if the price drops below a specified threshold (currently set to $60).
Automatic Monitoring: The script runs continuously, checking the price once every 24 hours.
