# 📊 Marketing Campaign Performance Analysis

## Project Overview

This project analyzes marketing campaign performance using Python.

The goal was to clean the dataset, create useful marketing KPIs, compare campaign performance, and answer business questions related to revenue, ROI, conversions, channels, and regions.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset

The dataset contains approximately 3,000 marketing campaign records with information such as:

- Campaign Name
- Marketing Channel
- Region
- Impressions
- Clicks
- Spend
- Conversions
- Revenue
- Device

---

## 🧹 Data Cleaning

The cleaning process included:

- Standardizing inconsistent categorical values
- Removing unnecessary spaces from text values
- Handling missing values
- Checking for duplicates
- Identifying invalid numerical values
- Detecting statistical outliers
- Verifying data types

---

## ⚙️ Feature Engineering

New marketing KPIs were created from the original data:

- **CTR (Click-Through Rate)**  
  Measures the percentage of impressions that resulted in clicks.

- **Conversion Rate**  
  Measures the percentage of clicks that resulted in conversions.

- **ROI (Return on Investment)**  
  Measures campaign return compared with campaign spending.

- **Revenue per Conversion**  
  Measures the average revenue generated from each conversion.

---

## 🔍 Business Questions

The analysis focused on questions such as:

1. Which marketing channel generated the highest total revenue?
2. Which channel achieved the highest average ROI?
3. Which campaign generated the most conversions?
4. Which region generated the highest total revenue?
5. How did revenue change over time?

---

## 💡 Key Findings

- 🥇 **Google Ads** generated the highest total revenue.
- 📈 **Instagram** achieved the highest average ROI.
- 🎯 **Ramadan Offer** generated the highest total number of conversions.
- 📍 **Cairo** generated the highest total revenue among the analyzed regions.

---

## 📊 Visualizations

### 💰 Total Revenue by Channel

![Revenue by Channel](images/revenue_by_channel.png)

---

### 📈 Average ROI by Channel

![Average ROI by Channel](images/roi_by_channel.png)

---

### 🎯 Total Conversions by Campaign

![Conversions by Campaign](images/conversions_by_campaign.png)

---

### 📍 Total Revenue by Region

![Revenue by Region](images/revenue_by_region.png)

---

## 🧠 What I Learned

Through this project, I practiced the complete data analysis workflow:

**Raw Data → Exploration → Cleaning → Feature Engineering → Analysis → Visualization → Business Insights**

One of the main lessons from the project was that statistical outliers should not always be removed automatically. Some unusual values represented genuinely high-performing campaigns, so they were investigated before deciding whether to keep or remove them.

---

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open `marketing_campaign_analysis.ipynb`.
3. Make sure `marketing_dataset.xlsx` is in the project folder.
4. Run the notebook cells in order.
