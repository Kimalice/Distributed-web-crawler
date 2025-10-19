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

🚀 Getting Started (Conceptual)

You can run the coordinator (Flask API) and start multiple workers on different machines or processes to simulate distributed crawling.

# 1. Start Flask Coordinator
python coordinator.py

# 2. Run Worker Nodes
python worker.py
python worker.py  # You can scale as many as you want


🔒 Note: Source code is not publicly included in this repository. This project serves as a showcase of architecture, system design, and real-world application of distributed crawling.

## 📊 Output Example (CSV)
<img width="975" height="655" alt="DWC 1" src="https://github.com/user-attachments/assets/64b24fe7-eb0b-42c7-9257-eeabfe4bfd45" />
<img width="970" height="639" alt="DWC 6" src="https://github.com/user-attachments/assets/85b9bc72-656c-43b9-a140-50cd4d979402" />
<img width="1024" height="685" alt="DWC 7" src="https://github.com/user-attachments/assets/c9a27496-0568-485c-b7d9-6d5f086cdad9" />


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
