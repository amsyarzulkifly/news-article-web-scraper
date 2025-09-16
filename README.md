# 📰 Multi-Source News Web Scrapers

This repository contains **Python web scrapers** to collect news articles from multiple online news sources.  

Each scraper retrieves **titles, dates, links, and article content** for a given query or search term and stores the results in a **pandas DataFrame**, which can be exported to CSV for further analysis.

**📝 Note**: Detailed instructions and usage for each scraper are included in the respective files.

## 📌 News Sources Included

1. **BBC News**
2. **CNBC**
3. **Investopedia**
4. **New York Post**
5. **NPR**
6. **NY Daily News**
7. **Reuters**

## 🔧 General Requirements

- Python 3.8+  
- Libraries: `requests`, `BeautifulSoup4`, `pandas`, `selenium`  
- WebDriver for Selenium (e.g., ChromeDriver) for sites with dynamic content  
