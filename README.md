# Amazon Web Scraper

A Python-based web scraper that extracts product details, prices, and ratings from Amazon using BeautifulSoup and Requests. The data is saved for analysis, making it useful for price tracking and market research.

## Features
- Scrapes product details, prices, and ratings from Amazon
- Uses BeautifulSoup for parsing HTML content
- Stores extracted data for further analysis
- Can be used for price tracking and market research

## How to Run

### Step 1: Clone the Repository  
```bash
git clone https://github.com/nipungoel24/Amazon-Web-Scraper.git
cd Amazon-Web-Scraper
```

### Step 2: Create and Activate a Conda Environment  
```bash
conda create -n amazon_scraper python=3.10
conda activate amazon_scraper
```

### Step 3: Install Dependencies  
```bash
pip install -r requirements.txt
```

### Step 4: Run the Script  
```bash
python amazon_scraper.py
```

## Future Enhancements
- Implement Selenium for dynamic content scraping
- Store scraped data in a database
- Automate daily/weekly price tracking
- Add multi-threading for faster data extraction

## Contributions  
Feel free to fork the repo and open a pull request with your improvements!
