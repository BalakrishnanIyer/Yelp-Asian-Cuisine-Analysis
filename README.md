# 🍽️ Yelp Asian Cuisine Restaurant Analysis

## 📌 Project Overview
This project analyzes the performance of **Asian Fusion cuisine restaurants** using Yelp data. We explore restaurant trends, identify high-rated locations, and analyze competition levels in different cities. The project uses **MongoDB**, **ETL processing**, and **data visualization** to derive key insights.

## ❓ Business Question
**How is the performance of restaurants that serve Asian cuisine? Is there scope for improvement in any area?**

## 🔍 Key Insights
1. **Data Extraction & Filtering**:
   - Pulled data from **Yelp's MongoDB database**.
   - Converted JSON data into tabular format.
   - Filtered only **restaurant-related businesses**.

2. **Identifying Trends**:
   - Extracted **Asian Fusion** restaurants.
   - Created a **pie chart** to analyze restaurant distribution.

3. **Rating Analysis**:
   - Filtered restaurants with **4-star and above ratings**.
   - Identified **Boston and Orlando** as top cities with high-rated Asian Fusion restaurants.
   - Created **bar charts** to compare cities.

4. **Competition & Demand**:
   - Analyzed restaurant counts per **postal code**.
   - Found that **Boston (02118)** has the **highest number of Asian Fusion restaurants**, indicating **high demand but high competition**.
   - **Orlando** shows **good demand and lower competition**, offering an opportunity for new restaurants.

## 🛠️ Technologies Used
- **MongoDB** – Data storage and retrieval.
- **ETL Processing** – JSON to Table transformation.
- **KNIME** – Workflow automation & data filtering.
- **Data Visualization** – Pie charts, bar graphs for insights.

## 📂 Project Files
- **`Yelp_Project3_Team11.knwf`** – KNIME workflow for data extraction & transformation.
- **`Yelp Data Transformation.png`** – Process flow of the data pipeline.

## 📊 Visualization Sample
![Yelp Data Transformation](images/Yelp_Data_Transformation.png)

## 🚀 How to Use
1. Download and open `Yelp_Project3_Team11.knwf` in **KNIME**.
2. Connect to the MongoDB dataset and run the workflow.
3. Analyze the **Asian Fusion** restaurant trends and ratings.
4. Use the **bar charts and pie charts** to derive insights.

## 🔗 Future Scope
- Expand analysis to other cuisine types.
- Integrate **machine learning models** to predict restaurant success based on past trends.

---

📢 **Connect with me**: [https://www.linkedin.com/in/balakrishnan-iyer-811436143]  
🔗 **Project Link**: (https://github.com/BalakrishnanIyer/Yelp-Asian-Cuisine-Analysis)
