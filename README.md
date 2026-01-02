# Airbnb Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an **Airbnb listings dataset** to understand listing distribution, pricing behavior, neighborhood trends, and user engagement over time. The analysis uses visualizations to uncover meaningful patterns that can support business insights and future modeling.

---

## 📊 Dataset Description

The dataset contains information related to Airbnb listings, including:

* Room type (Entire home/apt, Private room, Shared room, Hotel room)
* Neighborhood group (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
* Price of listings
* Review information and last review dates

The dataset reflects real-world Airbnb data and may contain inconsistencies such as missing values or spelling variations.

---

## 🔍 Analysis Performed

### 1. Room Type Distribution

* Analyzed the frequency of different room types.
* Found that **Entire home/apt** and **Private rooms** dominate the listings.
* Shared rooms and hotel rooms form a very small portion of the dataset.

**Insight:** Airbnb users show a strong preference for private accommodations, highlighting the platform’s peer-to-peer housing focus.

---

### 2. Neighborhood Group Distribution

* Visualized listings across neighborhood groups using a count plot.
* **Manhattan and Brooklyn** have the highest concentration of listings.
* **Queens** has moderate representation, while **Bronx and Staten Island** have minimal listings.

**Insight:** Airbnb activity is heavily concentrated in central and high-demand urban areas.

**Note:** Minor inconsistencies in neighborhood naming indicate the need for data cleaning before advanced analysis.

---

### 3. Price vs Room Type

* Used box plots to compare pricing across room types.
* **Entire home/apt and Hotel rooms** show higher median prices and wider variability.
* **Private and Shared rooms** are generally more affordable.

**Insight:** Room type significantly influences pricing, with entire homes showing the greatest price variability due to differences in size, location, and amenities.

---

### 4. Reviews Over Time

* Analyzed the number of reviews aggregated by month.
* Observed a general upward trend with sharp spikes during certain periods.
* Flat regions in later years suggest missing or future-dated data.

**Insight:** Review trends act as a proxy for booking activity and user engagement, while spikes may correspond to seasonal demand or external events.

---

## 🧹 Data Quality Considerations

* Inconsistent category labels (e.g., misspellings in neighborhood names)
* Missing or future review dates
* Class imbalance across room types and neighborhoods

These issues should be addressed before applying machine learning models or forecasting.

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🎯 Conclusion

This EDA provides valuable insights into Airbnb listing patterns, pricing behavior, and user engagement trends. The findings can support pricing strategies, location-based analysis, and serve as a foundation for predictive modeling.

---

## 🚀 Future Scope

* Data cleaning and preprocessing
* Price prediction models
* Demand forecasting using time-series analysis
* Location-based recommendation systems

---

*This project demonstrates practical EDA skills relevant to data analysis and data science roles.*
