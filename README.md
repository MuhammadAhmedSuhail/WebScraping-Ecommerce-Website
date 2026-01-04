# WebScraping Ecommerce Website Daraz.pk

## Project Description
This project is a web scraping tool that extracts data from the e-commerce website Daraz.pk. The tool can scrape reviews of a single product page, search for products using a keyword search and return the top 80 elements for that keyword, and extract products on a flash sale and return the product name, price, discounted price, top 3 reviews, and rating.

## Approach
The project uses Python and the Selenium library for web scraping. The tool navigates through the website's HTML structure to locate the data and then extracts it using Selenium's built-in methods. The data is then saved in a CSV file for further analysis.

### Scraping Reviews of a Single Product Page
To scrape reviews of a single product page, the tool takes the URL of the product page as input and then extracts the review data, including the review text and the reviewer's name, rating, and date of review.

### Keyword Search
To search for products using a keyword search, the tool prompts the user to enter a search query and then returns the top 80 elements for that keyword. The data returned includes the product name, price, rating, and number of reviews.

### Flash Sale Products
To extract products on a flash sale, the tool navigates to the flash sale section of the website and then extracts the product data, including the product name, price, discounted price, top 3 reviews, and rating.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python 3.x installed on your machine. You can download the latest version of [Python](https://www.python.org/downloads/) here.
</br>
You will also need to have Anaconda on your machine. You can download the latest version of [Anaconda](https://www.anaconda.com/) here.

### Installing
Clone this repository onto your local machine.
```
git clone https://github.com/MuhammadAhmedSuhail/WebScraping-Ecommerce-Website.git
```
Install the required packages.
```
pip install -r requirements.txt
```
Run `Scrape.ipynb` to run the scrapper of Daraz.pk and get the required data as output.

## Built with:
- Python3 - Programming Language Used
- Skimage - Library used for reading/writing and formatting the image
- Matplotlib - Library used for displaying the image 

## Conclusion
This project demonstrates how web scraping can be used to extract data from e-commerce websites, such as Daraz.pk. The tool developed in this project can be used to gather insights about products on Daraz.pk and to compare prices, ratings, and reviews across different products.

## Author:
- Muhammad Ahmed Suhail








