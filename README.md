Python Web Scraping App for Amazon Product Price Tracking
This Python web scraping app is designed to scrape the price of a specified Amazon product, upload the product name and price into a CSV file, and perform this task automatically every 48 hours. The collected data can be used for price checking and trend analysis.

Features
Scrapes the price of an Amazon product specified by the user.
Automatically uploads the product name and price into a CSV file every 48 hours.
Easy-to-use Jupyter Notebook interface.
Usage
Clone the Repository: Clone this repository to your local machine.

Install Dependencies: Ensure you have the required Python packages installed. You can install them using pip:

Copy code
pip install requests beautifulsoup4 pandas
Run the Jupyter Notebook: Open the Jupyter Notebook Amazon_Product_Price_Tracking.ipynb in your Jupyter Notebook environment.

Specify Amazon Product URL: In the notebook, specify the URL of the Amazon product you want to track.

Run the Notebook Cells: Execute the notebook cells to scrape the product price, save it to the CSV file, and schedule the task to run automatically every 48 hours.

Disclaimer
This web scraping app is provided for educational purposes only. Scraping Amazon's website may violate their terms of service, and it is your responsibility to ensure compliance with applicable laws and regulations. Use at your own risk.
