# 📊 Smart Price Monitor Scraper & Dashboard

A full-stack price monitoring application that automatically scrapes web data using **Scrapy**, stores structured product records in a **Neon Cloud PostgreSQL** database, and serves data via a **FastAPI** REST API with an interactive frontend dashboard.

---

## 🚀 Features

* **Automated Web Scraping:** Uses Scrapy to extract product titles, prices, stock availability, and URLs.
* **Cloud Database Storage:** Integrated PostgreSQL pipeline (`PostgresPipeline`) to sync scraped items directly to Neon Cloud DB.
* **FastAPI Backend:** Provides structured REST API endpoints for accessing product catalog and automated stats.
* **Interactive Dashboard:** Modern UI to view real-time scraped products and database status.
* **Swagger API Documentation:** Built-in interactive API testing environment.

---

## 🛠️ Tech Stack

* **Scraper:** Python, Scrapy, Twisted
* **Backend:** FastAPI, Uvicorn, Pydantic
* **Database:** PostgreSQL (Neon.tech), SQLAlchemy
* **Frontend:** HTML5, Tailwind CSS / JavaScript

---

## 💻 How to Run Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/hinacsag001-sudo/price-monitor-scraper.git](https://github.com/hinacsag001-sudo/price-monitor-scraper.git)
cd price-monitor-scraper