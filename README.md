# Amazon-Product-Scraper
Python project to scrape mobile phone data from Amazon Canada, extracting product names, prices, and review counts. The data is saved as a CSV and analyzed to visualize price distribution and top-reviewed products. Perfect for market analysis and tracking product performance.

# Amazon Mobile Phones Scraping and Analysis
Project Overview

This project demonstrates a web scraping application for extracting mobile phone data from Amazon Canada. It scrapes information from multiple pages and saves the extracted data into a CSV file. The data includes essential details such as product names, prices, number of reviews, and more. Additionally, the project provides a framework for analyzing the data to identify trends, such as the distribution of product prices and the most reviewed mobile phones.
Features

    Web Scraping: Automatically collects mobile phone data from Amazon Canada, spanning multiple pages.
    Data Extraction: Retrieves and stores key details, including:
        Product Name
        Price
        Number of Reviews
        Ratings
        Product Image URL
    Data Storage: Saves the extracted information in a CSV file for easy access and manipulation.
    Data Analysis: Includes basic analysis of the scraped data to provide insights, such as:
        Distribution of products by price category
        Top products based on review count

Requirements

To run this project, ensure you have the following Python libraries installed:

    pandas
    matplotlib
    seaborn
    selenium


    Setup WebDriver
        Ensure you have the appropriate WebDriver for your browser (e.g., ChromeDriver for Chrome).
        Place the WebDriver executable in a directory included in your system's PATH.

Usage

    Run the Scraping Script

    python

    python scrape_amazon_mobile.py

    This will start the scraping process, which will navigate through the pages and extract the data into a CSV file.

    Analyze the Data
        After scraping, use the provided Jupyter notebook or Python script to load the CSV file and perform analysis.
        Generate visualizations to explore the distribution of product prices and identify the top-reviewed products.

CSV File Format

The resulting CSV file contains the following columns:

    Product Name: Name of the mobile phone.
    Price: Price of the mobile phone.
    Number of Reviews: Total number of reviews for the product.
    Rating: Average rating of the product.
    Image URL: URL of the product image.

Analysis

The analysis includes:

    Price Distribution: A pie chart showing the distribution of products across different price ranges.
    Top Reviewed Products: A bar chart displaying the top 5 products with the highest number of reviews.

Notes

    The scraping logic is designed to work with the current structure of Amazon's mobile phone listings. Any changes to the website's structure may require updates to the scraping code.
    Ensure compliance with Amazon's terms of service when scraping data.
