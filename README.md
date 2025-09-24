# Shop Products Scraping & Analysis

## 📌 Overview
This project scrapes product data from the demo shop [scrapeme.live](https://scrapeme.live/shop/), stores the data in a CSV file, and performs **Exploratory Data Analysis (EDA)** to gain insights into products, prices, categories, stock, and tags.

---

## 🛠 Project Structure
- **taskw3.py** → Web scraping script that extracts product details and saves them into `shop_products.csv`.
- **ُeda_taskw3.py** → EDA script that analyzes the scraped data and generates visualizations.
- **shop_products.csv** → Output dataset containing scraped product information.

---

## 📊 Data Collected
Each product includes:
- `shop_name`: Product name  
- `shop_price`: Product price  
- `shop_product_url`: Product detail page link  
- `shop_image_url`: Product image link  
- `shop_sku`: SKU (if available)  
- `shop_categories`: Categories  
- `shop_tags`: Tags  
- `shop_stock_qty`: Quantity in stock (if available)  
- `shop_stock_text`: Stock description  
- `shop_description`: Product description  
- `shop_page`: Page number scraped from

---

## 🔍 Exploratory Data Analysis (EDA)
The analysis includes:
- Distribution of product prices  
- Top 10 products by stock quantity  
- Top 10 categories & tags  
- Product segmentation by price range (Cheap, Mid, Expensive, Luxury)  
- Products above vs below mean price  
- Top 10 products by total value (price × stock)  
- Average price trend across pages  
- Distribution of products across categories & price bins  
- Correlation between price and stock (heatmap)  

---

## 🚀 How to Run
1. Install required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas matplotlib
