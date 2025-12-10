# Agrimarket-Price-Analysis-Using-EDA
### Data-driven insights into India’s agricultural markets through structured scraping, cleaning, trend analysis, and visualization.

--- 
## 📌 Project Overview

This project analyzes agricultural commodity prices from Agmarknet, a government-operated open data platform for Indian mandi markets.
The goal is to extract data through web scraping, clean and structure it, and perform Exploratory Data Analysis (EDA) to uncover meaningful insights such as:

* Seasonal price fluctuations

* Market-wise price variation

* Commodity-level trends

* Factors influencing mandi price changes

This project demonstrates end-to-end data handling, starting from data extraction to visualization and insights.

---

## 🛠️ Project Workflow
#### 1️⃣ Web Scraping

* Extracted mandi-wise commodity data from Agmarknet

* Automated data collection for multiple dates, states & commodities

* Handled missing values, inconsistent formats, and dynamic HTML elements

(See: 01_WebScrapping_Agmarknet.ipynb)

#### 2️⃣ Data Cleaning & Preprocessing

* Removed duplicates & invalid entries

* Standardized column names and units

* Converted object data to numeric where required

* Handled outliers & missing values

* *Created structured final dataset for analysis

(See: 02_Data_Cleaning_Agmarknet.ipynb)

#### 3️⃣ Exploratory Data Analysis (EDA)

* Performed detailed analysis to answer key questions:

* Which commodities show highest volatility?

* How do prices differ across states?

* What are the seasonal patterns?

* Which markets consistently offer higher or lower prices?

#### Included visualizations such as:

***Line charts*** for price trends

***Heatmaps*** for correlations

***Bar charts*** for top/bottom markets

***Boxplots*** for commodity variation

(See: 03_Final_EDA_with_Visualization.ipynb)

 ---

## 📊 Key Insights

* Clear pricing seasonality observed for multiple commodities

* Certain states consistently show higher average mandi prices

* Large price dispersion indicates inconsistent supply chain efficiencies

* Strong correlation between arrival quantity and price variation for some commodities

#### * Several markets show predictable month-on-month patterns, useful for agri-intelligence

(Detailed insights available inside the EDA notebook & PDF report.)

---

## 📁 Repository Structure

```text
agmarknet-eda/
├── README.md
├── notebooks/
│   ├── 01_WebScrapping_Agmarknet.ipynb
│   ├── 02_Data_Cleaning_Agmarknet.ipynb
│   └── 03_Final_EDA_with_Visualization.ipynb
├── data/
│   └── Final_Agmarknet.xlsx
└── reports/
    └── AGMAnalysis.pdf
```



---      

## 🧰 Tech Stack Used

Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

Requests, BeautifulSoup (bs4)

---

## 🎯 Project Objectives

* Build a scalable workflow for agri-data scraping

* Clean and transform unstructured mandi data

* Identify market trends to support decision-making

* Demonstrate strong analytical and data-cleaning skills

* Present actionable insights for agriculture and supply-chain stakeholders

---

## 📄 Report

A detailed PDF report summarizing insights, charts, and conclusions is available in:

➡️ reports/AGMAnalysis.pdf

## Conclusion
##### The Agmarknet price analysis reveals clear and consistent patterns across commodities, markets, and seasons.
##### The data shows that agricultural prices are heavily influ enced by seasonality, arrival quantities, regional market dynamics, and supply-demand fluctuations.
##### Several commodities exhibit predictable price cycles, while others show high volatility driven by irregular arrivals and inconsistent market participation.

