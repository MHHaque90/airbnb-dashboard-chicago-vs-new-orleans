# 🏨 Airbnb Dashboard Project – Chicago vs New Orleans

This project is part of **The DataViz Challenge – Transforming EDA Projects to Dashboards**.

We analyze Airbnb operations in **Chicago** and **New Orleans** through comprehensive **data cleaning**, **EDA**, and **interactive visual dashboards** built in Tableau. The goal is to uncover trends, patterns, and key insights to support business decisions.

---

## 📊 Live Tableau Dashboard

🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Airbnb_Project_17538033691730/AirbnbHostReviewOverviewChicagovsNewOrleans?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📌 Problem Statement

> In the context of Airbnb operations, how can the utilization of Tableau Public facilitate a comprehensive comparative examination between **Chicago** and **New Orleans**, two diverse urban environments?

The objective is to **visualize shared attributes, differences, and unique patterns** of Airbnb listings in both cities using Tableau, enhancing the depth and clarity of analysis.

---

## 🧾 Dataset Details

- **Source:** [Inside Airbnb](http://insideairbnb.com/get-the-data/)
- **Cities Covered:** Chicago & New Orleans
- **Files Used:**
  - `chicago_airbnb_cleaned.csv`
  - `new_orleans_airbnb_cleaned.csv`
- **Key Attributes:**
  - `id`, `name`, `host_id`, `neighbourhood`, `room_type`, `price`, `number_of_reviews`, `availability_365`, etc.

---

## 🛠️ Tools Used

- **Jupyter Notebook** – For Data Cleaning and Preprocessing
- **Tableau Public** – For Dashboard Development
- **Pandas & NumPy** – For Data Wrangling
- **Matplotlib & Seaborn** – For Initial EDA

---

## 🔍 Phases of the Project

### ✅ Phase 1: Data Cleaning & Transformation
- Removed nulls, duplicates, and outliers.
- Standardized formats (e.g., price, availability).
- Created new columns for enhanced analysis (e.g., `Listings per Host`, `Price per Bedroom`).

### ✅ Phase 2: Data Visualization Categories
Visuals were created across four main categories:

1. **Overview of Airbnb**
   - Total Listings
   - Reviews per Month
   - Distribution by City

2. **Property Analysis**
   - Room Type Distribution
   - Listings per Host (Binned)
   - Top Hosts by City

3. **Pricing Analysis**
   - Price Distribution (Histogram)
   - Average Price by Room Type
   - Availability vs Price
   - Price per Bedroom by Room Type

4. **Host Analysis**
   - Avg Reviews by Room Type and City
   - Total Reviews by City
   - Avg Availability by City

### ✅ Phase 3: Dashboard Design
- **Dashboard 1:** Airbnb Overview
- **Dashboard 2:** Property & Price Insights
- **Dashboard 3:** Host Behavior & Reviews

All dashboards include **interactive filters** for a better user experience and actionable insights.

---

## 🧠 Key Insights

- **Chicago** generally had higher availability and listing counts, while **New Orleans** had more concentrated pricing ranges.
- **Entire home/apt** was the most common room type in both cities.
- Listings with more reviews were not always the most expensive or most available.
- Host behavior varied between cities, with different patterns in reviews and availability.

---

## 📂 Repository Structure

📦 airbnb-dashboard-project/
┣ 📁 data/
┃ ┣ 📄 chicago_airbnb_cleaned.csv
┃ ┗ 📄 new_orleans_airbnb_cleaned.csv
┣ 📁 dashboards/
┃ ┗ 📄 dashboard_screenshots.png (optional)
┣ 📄 Airbnb_EDA.ipynb
┗ 📄 README.md
---

## Author
Muhammad Hammaad Haque  
📧 Email: mhhaque90@gmail.com  
🔗 [Tableau Public Profile](https://public.tableau.com/app/profile/muhammad.hammaad.haque)

---

## 📣 Acknowledgement

This project was completed as part of the **AlmaBetter Data Science Program** for the **EDA to Dashboard Capstone Project**.
