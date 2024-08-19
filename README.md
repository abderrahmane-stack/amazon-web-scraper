# Amazon Web Scraper

A Python project developed in Jupyter Notebook to scrape product data from Amazon using BeautifulSoup and Requests. This project demonstrates how data analysts can utilize web scraping techniques to gather valuable information from e-commerce websites like Amazon.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project scrapes product data from Amazon using Python within a Jupyter Notebook environment. By leveraging BeautifulSoup and Requests libraries, you can extract details like product names, prices, ratings, and more. The data is stored in a pandas DataFrame and can be exported to a CSV file for further analysis.

## Features

- Scrapes product names, prices, and ratings from Amazon.
- Handles pagination to scrape multiple pages of results.
- Saves scraped data to a CSV file for further analysis.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/amazon-web-scraper.git
   cd amazon-web-scraper
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Usage

1. **Open the `amazon_scraper.ipynb` notebook** in Jupyter.
2. Update the search query and URL in the notebook to your desired Amazon product.
3. Run the notebook cells step by step to scrape data.
4. The scraped data will be saved to a `products.csv` file in the project directory.

## Dependencies

- `beautifulsoup4`
- `requests`
- `pandas`
- `jupyter`

To install all dependencies, use:
```bash
pip install -r requirements.txt
```

## Disclaimer

This project is intended for educational purposes only. Web scraping can violate the terms of service of some websites, including Amazon. Always check the legality of scraping data from a website and make sure to respect their `robots.txt` file.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

