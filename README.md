# Web Scraping of Stock Market Data using Python & BeautifulSoup

This project scrapes real-time stock market data from [Finology Ticker](https://ticker.finology.in/) using `requests` and `BeautifulSoup`, then saves it as a structured CSV file for further analysis.

---

## 📄 What It Does
- Sends a request to the live URL of stock listings
- Parses HTML and extracts data from the table
- Creates a structured pandas DataFrame
- Saves the extracted data as a `.csv` file

---

## 🧪 Sample Data (First Few Rows)
| Company           | Price (Rs.) | Day High (Rs.) |
|------------------|-------------|----------------|
| HCC              | 50.30       | 51.18          |
| LIC Housing Fin. | 714.40      | 719.55         |
| Tata Steel       | 182.95      | 183.87         |

---

## 📁 Files
- `web_scraper.ipynb` — Python script to perform web scraping  
- `scraped_data.csv` — Output file with scraped results  
- `requirements.txt` — Python libraries to install  

---

## 🚀 How to Run

1. Clone this repo
2. Install dependencies:

```bash
pip install -r requirements.txt
