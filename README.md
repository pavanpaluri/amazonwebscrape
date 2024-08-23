# amazonwebscrape
# Amazon Web Scraper

This Python script scrapes product details from an Amazon product page, including the product title, price, and rating.

## Prerequisites

- Python 3.x installed on your system.
- Install the required libraries using pip:

    ```bash
    pip install requests beautifulsoup4
    ```

## Setup

1. **Clone the Repository**: Clone this repository to your local machine.

    ```bash
    git clone https://github.com/yourusername/amazon-web-scraper.git
    ```

2. **Navigate to the Directory**:

    ```bash
    cd amazon-web-scraper
    ```

3. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Update the Script**: Edit the `amazon_scraper.py` file to include the Amazon product URL you want to scrape. Replace the example URL with your desired product URL:

    ```python
    url = 'https://www.amazon.com/dp/B08N5WRWNW/'  # Replace with the URL of the product you want to scrape
    ```

## Usage

1. **Run the Script**: Execute the script using the following command:

    ```bash
  python_amazon_scrape.ipynb
    ```

2. **Check the Output**: After running the script, a ipynb file named `amazon_scrape_final.ipynb  will be created in the same directory, containing the scraped product details.

## Example Output

The `amazon_scrape_final.ipynb` file will look like this:

```json
{
    "title": "gaming| playstation 4",
    "price": "$619",
    "rating": "4.7 out of 5 stars"
}
