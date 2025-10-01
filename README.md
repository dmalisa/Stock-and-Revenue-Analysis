# 📊 Stock Data Collection & Analysis  

## 📌 Project Overview  
This lab focused on learning how to **collect, clean, and analyze financial data** from various online sources. Using **web scraping** techniques and financial APIs, I extracted stock and revenue data for major companies and visualized their performance over time.  

## 📊 Dataset Details  
- **Companies Analyzed**: Tesla, GameStop  
- **Data Sources**:  
  - **Yahoo Finance API (`yfinance`)** – Stock prices and financial information  
  - **Web Scraping with BeautifulSoup** – Extracted revenue tables and financial data from websites  
- **Timeframe Covered**: Up to **June 2021**  

## 🔍 Data Collection & Cleaning Steps  
- **Web Scraping**: Used `BeautifulSoup` to extract financial tables from websites.  
- **API Data Extraction**: Leveraged `yfinance` to gather stock price history.  
- **Data Wrangling**: Cleaned and merged stock price data with revenue tables for analysis.  

## 🛠️ Tools & Libraries Used  
- **Python** (Jupyter Notebook)  
- **yfinance**: Fetching stock data  
- **BeautifulSoup**: Web scraping tables  
- **Pandas**: Data manipulation  

## 📈 Key Insights & Results  
- Visualized the **stock price trends** of Tesla and GameStop.  
- Compared **company revenues** up to June 2021.  
- Learned how to combine **scraped web data with financial APIs** for richer insights.  

### 🔹 Tesla  
![Tesla Stock Trend](images/tesla_stock.png)  
*Tesla’s historical share price started relatively low, rose significantly with a peak around $300, and then declined slightly but stayed above $200.*  

![Tesla Revenue](images/tesla_revenue.png)  
*Tesla’s revenue shows a steady concave increase from the 2000s through 2021, reflecting consistent growth in sales.*  

### 🔹 GameStop  
![GameStop Stock Trend](images/gamestop_stock.png)  
*GameStop’s stock price remained steady for years, then spiked sharply, reaching a peak around $80 before stabilizing. The lowest values hovered near $0.*  

![GameStop Revenue](images/gamestop_revenue.png)  
*GameStop’s revenue climbed steadily over the years, peaking near $10,000 million, before dropping to around $6,000 million in 2020.*  
 
