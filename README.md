# Amazon & Jumia Product Scraper

This project contains Python scripts to scrape product data from two popular e-commerce websites:

- **Amazon.eg**: Men’s Jeans category
- **Jumia.com.eg**: Cellphones category

The scraper uses Selenium with BeautifulSoup to handle JavaScript-loaded content and extract product details, saving them into CSV files.

---

## Features

- Scrapes multiple pages from both websites
- Extracts key product information:
  - Product Name
  - Price
  - Rating (if available)
  - Number of Reviews (if available)
  - Product URL
  - Image URL
  - Brand (extracted from product name)
- Saves results into separate CSV files for each site/category
- Headless browser scraping with Selenium for efficiency and automation

---

## Requirements

- Python 3.x
- Google Chrome browser installed
- ChromeDriver compatible with your Chrome version ([Download here](https://chromedriver.chromium.org/downloads))
- Python packages: `selenium`, `beautifulsoup4`, `pandas`

Install packages via:

```bash
pip install selenium beautifulsoup4 pandas
