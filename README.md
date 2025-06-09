# 🏙️ New York Airbnb Data Analysis (Python)

<p align="center">
  <img width="1000" src="https://capsule-render.vercel.app/api?type=waving&color=F5B7B1&height=200&section=header&text=New%20York%20Airbnb%20Insights&fontSize=35&fontAlign=50&fontAlignY=35&desc=Exploring%20rental%20trends%20to%20uncover%20tourism%20patterns&descAlign=50&descAlignY=55&animation=fadeIn">
</p>

## 🎯 Project Objective
Explore and analyze New York City Airbnb listings using Python to uncover pricing trends, neighborhood popularity, availability patterns, and insights that can support better rental decisions for hosts and travelers.

---

## 🗂 Dataset Overview
- **Source**: [New York Airbnb dataset](https://github.com/molie01/New_York_Airbnb/blob/main/New%20York%20Airbnb%20dataset.csv)
- **Fields**: Listing ID, Host ID, Neighbourhood Group, Neighbourhood, Room Type, Price, Minimum Nights, Number of Reviews, Availability, etc.

---

## ❓ Key Questions Answered
- What is the price range of Airbnb listings in NYC, and how are prices distributed?
- Which boroughs have the most listings and how does pricing differ by area?
- How does room type affect pricing and availability?
- Is there a link between number of reviews and listing price?
- What Airbnb features are most correlated?
- Where are the Airbnb listings concentrated geographically?
- What patterns exist among pricing, nights, reviews, and availability?
- Charts Display [View Visual Highlights](#visual)

---

## 🛠 Process Overview
- Loaded and cleaned dataset using **Pandas**
- Removed missing values and filtered out extreme outliers
- Performed exploratory data analysis (EDA) using **Matplotlib** and **Seaborn**
- Aggregated and grouped data by borough, room type, and availability
- Visualized pricing, listing count, and review distribution trends

---

## 📊 <a id="visual">Visual Highlights</a> 

### 📉 1. Boxplot of Airbnb Prices (< $1500)
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Boxplot%20of%20Airbnb%20Prices%20(%3C%20%241500).png" width="700" alt="Boxplot of Airbnb Prices">
</p>

### 💲 2. Airbnb Price Distribution
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Airbnb%20Price%20Distribution.png" width="700" alt="Airbnb Price Distribution">
</p>

### 📅 3. Airbnb Availability Distribution
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Airbnb%20Availability%20Distribution.png" width="700" alt="Airbnb Availability Distribution">
</p>

### 🗺️ 4. Airbnb Neighbourhood Distribution
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Airbnb%20Neighbourhood%20Distribution.png" width="700" alt="Price per Bed by Borough">
</p>

### 💬 5. Locality and Review Dependency
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Locality%20and%20Review%20Dependency.png" width="700" alt="Reviews vs Price">
</p>

### 🔁 6. Variable Relationships by Room Type (Pairplot)
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Variable%20Relationships%20by%20Room%20Type.png" width="700" alt="Pairplot of Airbnb Variables">
</p>

### 🌍 7. Geographical Distribution of Airbnb Listing
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Geographical%20Distribution%20of%20Airbnb%20Listing.png" width="700" alt="Geographical Distribution of Airbnb Listings">
</p>

### 📈 8. Correlation Between Airbnb Metrics (Heatmap)
<p align="center">
  <img src="https://github.com/molie01/New_York_Airbnb/blob/main/Correlation%20Between%20Airbnb%20Metrics.png" width="700" alt="Correlation Heatmap">
</p>

---

## 🔍 Key Insights
- **Manhattan and Brooklyn** dominate the Airbnb market, with Manhattan commanding the highest average prices—highlighting premium demand in central boroughs.
- **Entire home/apt listings** are significantly more expensive but offer less availability, suggesting a trade-off between revenue potential and occupancy rates.
- **Listings with moderate availability (200–300 days/year)** tend to receive more reviews, indicating a sweet spot for maximizing engagement and maintaining listing visibility.
- Identified **pricing anomalies** and outlier behavior, supporting the need for data-informed pricing strategies to stay competitive.
- Revealed **strong patterns between room types and key metrics** (e.g. price, reviews), enabling hosts and investors to optimize listing setup for specific target audiences.
- Geo-visualizations uncovered **clusters of high-activity zones**, offering strategic guidance for expansion, promotion, or investment.

---

## 📌 Final Conclusion
This project highlights key dynamics of New York City’s Airbnb market, including pricing trends, neighborhood hotspots, and guest behavior patterns. The insights support more strategic decisions for hosts, travelers, and investors—such as identifying profitable listing types, optimizing availability, and targeting high-demand locations. These findings demonstrate the value of data-driven thinking in understanding and navigating competitive rental markets.

---

## 🧰 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook for analysis and visualization

> 🚀 Designed to support smarter hosting strategies and deeper tourism insights through accessible Python-based data exploration.
