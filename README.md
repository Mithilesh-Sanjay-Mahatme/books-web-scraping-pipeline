📚 Books Web Scraping Pipeline

🔍 Overview

This project demonstrates a simple end-to-end web scraping workflow using Python. The goal was to extract structured data (book title, price, rating, availability) from a public website and convert it into an analyzable dataset.


⚙️ Tech Stack
-  Python
-  requests
-  BeautifulSoup
-  pandas


🚀 Features
- Scrapes book data across multiple pages (pagination handling)
- Extracts key attributes:
  - Title
  - Price
  - Rating
  - Availability
- Performs basic data cleaning and transformation
- Exports structured dataset to CSV


📊 Sample Output
Clean tabular dataset ready for analysis
Can be extended for:
- Price trend analysis
- Inventory tracking
- Data pipeline integration


🧠 Key Learnings
- Handling pagination in web scraping
- Parsing HTML using BeautifulSoup
- Data cleaning using pandas
- Structuring raw data into usable format


🔄 Future Improvements
- Add error handling and retry logic
- Store data in a database (PostgreSQL / SQLite)
- Schedule scraping using cron or workflow tools
- Scale into a production-ready data pipeline


📁 Output
-  books_to_scrape.csv
