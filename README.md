# 🏠 Paris Airbnb Price Analysis

This project explores over 86,000 Airbnb listings in Paris using Python. It includes data cleaning, exploratory data analysis (EDA), and visualizations to uncover pricing trends, room type patterns, and listing availability.

---

## ✅ Objectives

- Clean and prepare raw Airbnb data
- Explore price distribution, reviews, and availability
- Analyze trends across room types and neighborhoods
- Generate useful visualizations for business insights

---

## 🧰 Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

---

## 📊 Key Insights

### 🔹 Price Distribution
- Most listings are priced under €200
- A few luxury listings priced above €1000 (outliers)

### 🔹 Room Type Analysis
- Private rooms and entire homes dominate the listings
- Shared and hotel rooms form a small minority

### 🔹 Neighbourhood Trends
- Certain neighborhoods have significantly higher average prices

### 🔹 Reviews & Price
- Listings with more reviews tend to be priced lower (possibly budget-friendly)

### 🔹 Availability
- Many listings are available 300+ days/year (likely full-time rentals)

---

## 📈 Visualizations

- Histogram of prices
- Bar chart of average price by room type
- Pie chart of room type distribution
- Top 10 most expensive listings
- Histogram of availability across listings
- Scatter plot of price vs number of reviews

---

## 📁 Project Structure

<pre> airbnb-paris-analysis/ ├── data/ │ ├── listings.csv # Raw dataset from Inside Airbnb │ └── paris_airbnb_cleaned.csv # Cleaned dataset after preprocessing ├── notebooks/ │ └── paris_airbnb_analysis.ipynb # Main analysis notebook ├── requirements.txt # Python dependencies └── README.md # Project overview and documentation </pre>


---

## 💡 Next Steps

- Add SQL queries for advanced insights (optional)
- Build a Streamlit app for interactive exploration
- Compare trends across multiple cities

---

## 📎 Data Source

Data from [Inside Airbnb – Paris](http://insideairbnb.com/get-the-data.html)
