
# 🌐 Web-Based Admin Panel with Web Scraping

This project is a cloud-hosted admin panel that scrapes data from a public website, stores it in a cloud database (MongoDB Atlas), and displays it in a table with pagination. The scraping is triggered on-demand via a button in the admin dashboard.

---

## 🚀 Live Demo

Frontend: [Vercel Link](https://your-vercel-app-url.vercel.app)  
Backend: [Render/Railway Link](https://your-backend-service-url.onrender.com)

---

## 📚 Data Source

- Website: [https://books.toscrape.com](https://books.toscrape.com)
- Scraped Data: Book title, price, and rating

---

## 🛠 Tech Stack

| Layer        | Tech Used                 |
|--------------|---------------------------|
| Frontend     | React, Bootstrap          |
| Backend      | Node.js, Express          |
| Scraper      | Cheerio (server-side JS)  |
| Database     | MongoDB Atlas             |
| Deployment   | Vercel (frontend), Render or Railway (backend) |

---

## ✨ Features

- 🔐 Simple admin interface (optional Firebase auth)
- 🧼 “Scrape Now” button to fetch latest book data
- 📊 Table view with title, price, and rating
- ☁️ Hosted on cloud platforms

---

## 🔧 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/scraper-admin-panel.git
cd scraper-admin-panel
