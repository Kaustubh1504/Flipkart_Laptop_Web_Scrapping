# Web Scraping Project - Flipkart Laptop Data

This project is a web scraping script written in Python using the BeautifulSoup library to extract laptop data from the Flipkart website. The script retrieves information such as product names, prices, ratings, descriptions, and images for Acer laptops.

## Requirements

To run the script, you need the following:

- Python 3.x
- BeautifulSoup library
- Pandas library
- Requests library

You can install the required libraries by running the following command:

```
pip install beautifulsoup4 pandas requests
```

## Usage

1. Clone the repository or download the script `flipkart_laptop_scraper.py`.
2. Open the script in a text editor and update the `url` variable with the desired Flipkart search URL.
3. Run the script using the command:

   ```
   python flipkart_laptop_scraper.py
   ```

4. The script will scrape the data from Flipkart and save it to a CSV file named `lenovo_products.csv`.
5. Check the generated CSV file for the scraped data.

## Output

The script outputs a CSV file containing the following columns:

- Name: The name of the laptop product.
- Regular Price: The regular price of the laptop.
- Links: The link to the product page on Flipkart.
- Description: The detailed description of the laptop.
- Short Description: The short description of the laptop.
- Image: The URL of the main product image.
- Image Gallery: URLs of additional images of the product.
- Brand: The brand of the laptop (in this case, "Acer").
