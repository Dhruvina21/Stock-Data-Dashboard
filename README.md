# Stock Data Dashboard – Extracting & Visualizing Financial Data

## The Business Problem
A new startup investment firm needed a way to help clients make 
smarter investment decisions. The challenge? Raw financial data 
is scattered across multiple sources — stock exchanges, quarterly 
earnings reports, and financial websites — making it nearly 
impossible to spot trends at a glance.

**My role:** Acting as a Data Scientist, I was tasked with building 
an automated data pipeline that extracts, cleans, and visualizes 
historical stock prices and revenue data for key stocks — giving 
investors a clear, data-driven view of company performance.

---

## 🔍 The Approach
I analyzed two high-profile stocks with very different stories:

- 🚗 **Tesla (TSLA)** — A growth stock that transformed from a 
startup into one of the world's most valuable companies
- **GameStop (GME)** — A legacy retailer that became the center 
of one of the most dramatic short squeezes in stock market history

Data was collected using two techniques:
1. **yfinance API** — to extract historical daily stock prices
2. **Web Scraping (BeautifulSoup)** — to extract quarterly 
revenue reports from financial web pages

---

## 💡 Key Findings

| Stock | Insight |
|-------|---------|
| Tesla | Share price grew from ~$1 in 2010 to ~$300 by 2021, mirroring explosive revenue growth from $27M to $10B+ |
| 🎮 GameStop | Revenue showed consistent seasonal spikes (holiday seasons) but an overall declining trend, while the stock price spiked dramatically to ~$85 in Jan 2021 due to the Reddit short squeeze |

---

## 📊 Dashboard Overview

### Tesla Dashboard
- **Historical Share Price** — Flat for nearly a decade, 
then explosive growth from 2019-2021
- **Historical Revenue** — Steady climb from near zero 
to over $10,000M, validating the price surge

### GameStop Dashboard
- **Historical Share Price** — Years of stability followed 
by the infamous 2021 meme stock spike
- **Historical Revenue** — Clear seasonal cycles reflecting 
holiday shopping patterns, with a long-term declining trend 
signaling business model challenges

---

##  Tools & Skills Demonstrated
- **Python** — Data extraction and processing
- **yfinance** — Stock market data extraction via API
- **BeautifulSoup & Requests** — Web scraping financial data
- **Pandas** — Data cleaning and manipulation
- **Matplotlib** — Data visualization and dashboard creation
- **Jupyter Notebook** — Interactive analysis environment

---

## 📁 Repository Contents
| File | Description |
|------|-------------|
| `Revenue_Data_and_Building_a_Dashboard.ipynb` | Complete Jupyter notebook with all code, outputs and graphs |


## 📜 Data Sources
- Stock price data via **Yahoo Finance API (yfinance)**
- Revenue data scraped from 
**IBM Skills Network hosted financial pages**
- Part of the **IBM Data Analyst Professional Certificate** 
on Coursera
