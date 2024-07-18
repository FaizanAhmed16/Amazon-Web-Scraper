# 🪙 Crypto Data Scraper 🚀

Welcome to the **Crypto Data Scraper** project! This tool is designed to automatically scrape cryptocurrency data from CoinMarketCap, clean it, and visualize it for your analysis needs. Whether you're tracking the latest crypto trends or analyzing historical data, this scraper has got you covered.

## 📋 Features

- **Automated Data Extraction**: Scrapes cryptocurrency data from CoinMarketCap every minute.
- **Data Cleaning**: Utilizes pandas to clean and preprocess the data—corrects column names, resets indices, and removes null values.
- **Data Visualization**: Leverages seaborn and matplotlib to create insightful visualizations of the data.

## 🛠️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/crypto-data-scraper.git

2. **Install Dependencies**

  Ensure you have the necessary Python libraries installed:
  ```bash
  pip install pandas seaborn matplotlib requests
   ```
3. **API Key Setup**

   To run the scraper, you'll need your own API key from CoinMarketCap. Replace the placeholder in CryptoWebScraper.ipynb with your API key:
   ```bash
   'X-CMC_PRO_API_KEY': os.getenv('CMC_PRO_API_KEY')
   ```


**📊 Visualizations**

The scraper generates various visualizations including:

Cryptocurrency price trends over time
Market cap distributions
Volume comparisons

**📬 Contact**

For any questions or issues, feel free to reach out via email (faizan16ahmed@gmail.com) or open an issue on the GitHub repository.

Happy scraping! 🥳





