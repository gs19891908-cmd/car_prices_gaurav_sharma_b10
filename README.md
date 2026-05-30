# 🚗 Used Car Prices — Exploratory Data Analysis (EDA)

**Assignment | Python & Pandas | HeroVired Virtual Education**

---

## 📌 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on a real-world used car listings dataset (`car_prices.csv`).  
It covers data ingestion, cleaning, querying, and visualization using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** — all inside **Google Colab**.

---

## 📁 Repository Structure

```
├── car_prices_colab.ipynb   # Main notebook (all tasks & visualizations)
├── car_prices.csv           # Dataset — used car listings
├── submission_link.docx     # Submission document with repo link
└── README.md                # This file
```

---

## 📋 Tasks Covered

### Section 1 — Data Ingestion & Quality Profiling
| Task | Description |
|------|-------------|
| 1.1 | Load CSV, display first 5 rows, data types, record count |
| 1.2 | Dataset shape, column names and data types |
| 1.3 | Null detection (bar chart + heatmap), fill strategy (median/mode), deduplication |

### Section 2 — DataFrame Queries
| Task | Description |
|------|-------------|
| 2.1 | Average, minimum, and maximum selling price |
| 2.2 | All unique car colors |
| 2.3 | Number of unique brands and models |
| 2.4 | Cars with selling price > $165,000 |
| 2.5 | Top 5 most frequently sold car models |
| 2.6 | Average selling price by brand (make) |
| 2.7 | Minimum selling price by interior type |
| 2.8 | Highest odometer reading per year (descending) |
| 2.9 | New column: car age (2025 − model year) |
| 2.10 | Cars with condition ≥ 48 AND odometer > 90,000 |
| 2.11 | State with consistently highest prices for newer cars (year > 2013) |
| 2.12 | Best-value makes in excellent condition (top 20%) |

### Section 3 — Data Visualization & Insights
| Task | Description |
|------|-------------|
| 3.1 | Correlation heatmap of all numerical features |
| 3.2 | Bar chart — average selling price by model year |
| 3.3 | Line chart — average price vs odometer reading |
| 3.4 | Bar chart — number of cars sold per state |
| 3.5 | Bar chart — avg price by condition score (bin = 5) |
| 3.6 | Bar chart — car count by condition range (bin = 10) |
| 3.7 | Box plots — price distribution by car color (with & without outliers) |

---

## 🛠️ Libraries Used

- `pandas` — data loading, cleaning, querying
- `numpy` — numerical operations
- `matplotlib` — plotting
- `seaborn` — statistical visualizations
- `google.colab` — file upload in Colab environment

---

## 📊 Dataset

**File:** `car_prices.csv`  
**Source:** Provided as part of the HeroVired course assignment  
**Contents:** Used car listings with attributes including price, make, model, year, condition, odometer, color, interior, fuel type, and state

---

## 👤 Author

**Name:** Gaurav Sharma  
**Program:** CPDA B10 
**Institution:** HeroVired Virtual Education  

---

*© 2025 HeroVired Private Limited. All rights reserved.*
