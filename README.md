# 🕸️ AI Web Scraper 🚀

An intelligent web scraping solution powered by **Ollama**, **BrightData**, **Selenium**, and modern AI tools to extract, parse, and analyze web content in a smart, scalable way.

## 🔍 Overview

This AI Web Scraper is built to go beyond traditional scraping by integrating Large Language Models (LLMs) using **Ollama** and leveraging **BrightData’s proxy services** for reliable data extraction. Whether you're scraping e-commerce sites, news articles, or public datasets, this tool gives you an edge with automation and intelligence.

---

## ⚙️ Features

- ✅ **Headless Browser Automation** with Selenium
- 🤖 **Natural Language Processing** with LLMs via Ollama
- 🌐 **Proxy Rotation** with BrightData for anti-block scraping
- 🧠 **AI-Powered Content Filtering** and Semantic Extraction
- 📄 Save data in **CSV, JSON**, or push to **databases**
- 🛠️ Configurable via `config.yaml` or CLI
- 💡 Ready for cloud deployment and CI/CD integration

---

## 🧰 Tech Stack

| Tool         | Purpose                         |
|--------------|----------------------------------|
| 🐍 Python     | Core programming language        |
| 🧪 Selenium   | Web automation and scraping      |
| 🧠 Ollama     | LLM-based intelligent processing |
| 🌍 BrightData | Rotating proxies for scraping    |
| 📦 BeautifulSoup | HTML parsing                |
| 🐼 Pandas     | Data wrangling & export          |

---
## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/arshi9854/AI-Web-Scraper.git
cd AI-Web-Scraper
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```
### 3. Configure Settings

- Update the config.yaml or .env file to include your:

- BrightData credentials (proxy host, port, username, password)

- Ollama model and endpoint

- Scraping target URLs or keywords

### 4. Run the Scraper

```bash
python main.py
```
✅ Make sure BrightData Proxy Manager and Ollama with your selected LLM are running locally or remotely before executing.

### 🧠 How It Works

1) Scraper Initialization: Selenium starts a headless browser session for automation.

2) Proxy Assignment: BrightData dynamically rotates IPs and routes requests.

3) Page Parsing: BeautifulSoup extracts required data from HTML.

4) AI Analysis: Content is passed to Ollama, which uses LLMs to summarize, categorize, or interpret results.

5) Data Export: Parsed results are saved as CSV/JSON or pushed to a database.

### 🧪 Example Use Cases

🛒 E-commerce Scraping: Products, pricing, reviews

📰 News Aggregation: Summarize articles using AI

📊 Data Research: Academic or business intelligence scraping

🔍 SEO & Competitor Analysis: Keyword and content monitoring

### 💡 Future Improvements

✅ Dockerize the full stack for easier deployment

✅ Add GUI or Streamlit Dashboard

✅ Multi-threaded scraping and rate limiting

✅ MongoDB or PostgreSQL backend support

✅ Real-time scraping metrics and logging

✅ Drag & drop prompt editor for LLM configurations



