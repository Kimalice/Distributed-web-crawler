# 🚀 Distributed Web Crawler

## 📌 Overview

A **scalable distributed web crawler** built with **Python and Flask** that mimics how modern search engines like Google crawl, extract, and structure information from the web. This system uses multiple worker nodes coordinated through a central API to efficiently gather data and store it in structured format.

---

## 🔍 What is a Web Crawler?

A **web crawler** (also known as a spider or bot) is an automated tool that systematically browses the internet to discover pages, extract information, and gather links for further crawling. It is the backbone of **search engines, AI data pipelines, market research tools, and cybersecurity systems**.

---

## 🌐 Project Purpose

This crawler simulates a **distributed architecture** similar to how large-scale web crawlers work in real-world applications. It automatically extracts:

* ✅ URL
* ✅ Page Title
* ✅ Page Size
* ✅ First Paragraph / Meaningful Content
* ✅ All Outbound Links

This information is saved into structured CSV files for **data analysis, research, AI training, or automation workflows**.

---

## 🏗️ System Architecture

```
           ┌────────────────────────┐
           │  Flask Coordinator API │
           └────────────┬───────────┘
                        │
         ┌──────────────┴──────────────┐
         │                             │
┌────────▼───────┐             ┌───────▼────────┐
│ Worker Node 1  │             │ Worker Node 2  │
└────────┬───────┘             └───────┬────────┘
         │                             │
         └──────────────┬──────────────┘
                        │
                 CSV Output Storage
```

---

## 🛠️ Tech Stack

| Component     | Technology Used   |
| ------------- | ----------------- |
| Core Language | Python            |
| API Server    | Flask             |
| HTML Parsing  | BeautifulSoup     |
| HTTP Requests | Requests Library  |
| Concurrency   | Threading, Queues |
| Data Storage  | CSV Export        |

---

## 🔧 Key Features

* 🌐 **Distributed Architecture** (multiple workers)
* ⚡ **Real-time Task Assignment via API**
* 📄 **Automatic Data Extraction** (Title, URL, Content, Links)
* 📁 **CSV Export for Analytics**
* 🔄 **Scalable and Extensible Design**

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/distributed-web-crawler.git
cd distributed-web-crawler
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Start the Coordinator

```bash
python coordinator.py
```

### 4️⃣ Start Worker Nodes

```bash
python worker.py
```

---

## 📊 Output Example (CSV)
<img width="975" height="655" alt="DWC 1" src="https://github.com/user-attachments/assets/64b24fe7-eb0b-42c7-9257-eeabfe4bfd45" />

---

## 🌍 Why This Matters

In the age of **AI, automation, and real-time data**, web crawlers are the foundation for:

* 🤖 AI & LLM Training Datasets
* 📈 Business & Market Intelligence
* 🔐 Cybersecurity & Compliance
* 🧠 Knowledge Graphs and Research

> **Data is the new fuel — and web crawlers are the engines that extract it.**

---

## ✨ Future Enhancements

* Integration with **Databases (MongoDB, Elasticsearch)**
* Support for **JavaScript-rendered Websites**
* Dashboard for **Real-Time Monitoring**
* Deployment as a **SaaS Platform** for Lead Generation & Analytics

---

## 🤝 Contribute

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📬 Contact

If you’re passionate about **AI, automation, or data engineering**, connect with me on LinkedIn or GitHub.

---

### ⭐ If you find this project valuable, don’t forget to star the repository!
