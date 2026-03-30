# Airbnb Listings Data Analysis & Visualization

## 📌 Project Overview
This project analyzes Airbnb listing data using Python and MySQL to uncover insights about pricing, availability, host behavior, and customer engagement.

It follows a complete data analytics pipeline including data preprocessing, feature engineering, database storage, and visualization.

---

## 🎯 Objectives
- Understand dataset structure and variables
- Clean and preprocess raw data
- Perform feature engineering
- Store processed data in MySQL database
- Conduct analysis using Python
- Visualize trends and patterns

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL (XAMPP)
- SQLAlchemy
- Jupyter Notebook

---

## 📊 Dataset Information
The dataset contains **15,970 Airbnb listings** with features such as:

- Listing ID and name
- Host details (host_id, host_name)
- Location (latitude, longitude, neighbourhood)
- Room type (Private, Shared, Hotel)
- Price per night
- Reviews and ratings
- Availability (availability_365)

---

## 🔧 Data Preprocessing
- Filled missing values (e.g., reviews_per_month → 0)
- Converted date columns to datetime
- Created new features:
  - `days_since_last_review`
  - `price_category` (Low, Medium, High)
- Applied one-hot encoding to categorical variables
- Performed data validation and consistency checks

---

## 🗄️ Database Integration
- Cleaned data stored in MySQL using XAMPP
- Database managed via phpMyAdmin
- Python connected using SQLAlchemy

### Benefits:
- Efficient querying
- Structured storage
- Scalability

---

## 📈 Key Insights

### 🔹 Price Distribution
- Most listings fall in moderate price ranges
- Some extreme outliers exist

### 🔹 Room Type vs Price
- Entire homes and hotel rooms are more expensive
- Shared rooms are the cheapest

### 🔹 Reviews & Popularity
- Listings with more reviews tend to attract more users
- Reviews indicate trust and engagement

### 🔹 Availability Patterns
- Some listings are available year-round
- Others are seasonal or limited

---

## ⚠️ Challenges
- Handling missing review data
- Managing price outliers
- MySQL integration with Python
- Ensuring correct data types

---

## ▶️ How to Run

1. Clone repository:
```bash
git clone https://github.com/YOUR-USERNAME/airbnb-data-analysis.git
