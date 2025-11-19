# 💼 Zomato Restaurant Analysis – SQL + Python (EDA)

This project explores restaurant data from Zomato to understand food trends, pricing patterns, customer preferences, and ratings. The goal is to clean the data, analyse it using SQL and Python, and highlight insights that can support business decisions for food delivery platforms and restaurant chains.

---

## 📌 Project Overview

This analysis uncovers patterns in restaurant operations, customer behavior, and service models. It supports business decisions such as:

- Merchant segmentation
- Spend prediction
- Digital adoption tracking
- Customer satisfaction analysis


---

## 🛠 Tools and Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Data analysis and scripting |
| **MySQL** | Data storage and querying |
| **Jupyter Notebook** | Interactive analysis |
| **Pandas** | Data manipulation |
| **Seaborn & Matplotlib** | Data visualization |
| **dotenv** | Secure credential management |
| **Conda** | Environment isolation and reproducibility |

---

## 📊 Key Insights

- **Popular Restaurant Categories** — Bar chart showing dominant service types
- **Number of Ratings by Restaurant Type** — Line chart showing engagement levels
- **Most Rated Restaurant** — Identified top performer by rating count
- **Online Order Availability** — Pie chart showing digital adoption
- **Analyze Ratings** — Histogram revealing satisfaction spread
- **Approximate Cost for Two People** — Bar chart showing affordability clusters
- **Online vs Offline Orders – Rating Comparison** — Box plot comparing service quality
- **Order Mode Preferences by Restaurant Type** — Heatmap showing digital vs offline tendencies

---

## ✔ Steps Performed

1. **Data Loading** — Pulled from MySQL using secure `.env` credentials
2. **Data Cleaning** — Removed nulls, standardized cost and rating fields
3. **Exploratory Analysis** — Used Pandas and Seaborn to explore patterns
4. **Visualizations** — Created 8+ charts to communicate insights clearly

---

## 🔐 How to Setup/Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/AaravAnmol/Zomato-Restaurant-Analysis.git
   cd Zomato-Restaurant-Analysis

## 📁 Project Structure
Zomato-Restaurant-Analysis/
│
├── db.ipynb               # MySQL connection using .env
├── main.ipynb             # Data analysis and visualizations
├── Zomato_schema.sql      # SQL file to create and populate the database
├── .env                   # Environment variables (excluded from GitHub)
└── README.md              # Project documentation

## 🗄 SQL File

The `Zomato_schema.sql` file contains the database schema and sample data used in this project.  
This dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets) and included here for reproducibility.


## 🎯 Conclusion
This project highlights how combining SQL and Python helps in understanding restaurant trends and customer behaviour and showcases my ability to:
- Work with real-world data
- Apply structured business analysis
- Communicate insights through clear visualizations
- Build secure, modular, and reproducible workflow
