# 🌾 Forecasting Agricultural Commodity Prices Using Machine Learning

This project applies **data science and linear regression** techniques to forecast commodity prices for major crops such as **Wheat, Rice, and Maize**, helping farmers and market analysts make informed decisions.

---

## 📚 Project Objective

- Analyze historical crop prices using statistical methods.
- Visualize price trends and patterns.
- Build and evaluate a **machine learning model** (Linear Regression) to forecast future prices.

---

## 🗂️ Dataset

The dataset contains price records for various agricultural commodities collected from Indian markets. Each CSV file (Wheat.csv, Maize.csv, etc.) contains:
- `month`: Date in YYYY-MM format
- `commodity_name`: Name of the crop
- `avg_modal_price`: Average modal price of the crop in INR

You can find these in the `datasets/` folder.

---

## 📈 Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Calculate Mean, Median, and Mode  
   - Visualize price distributions using histograms and KDE plots  
   - Trend analysis over time

2. **Machine Learning Model**  
   - Convert date to numerical format  
   - Apply **Linear Regression** to predict future prices  
   - Evaluate performance using **Mean Squared Error (MSE)**

---

## 🛠 Tech Stack

- Python 🐍
- Pandas, Matplotlib, Seaborn
- scikit-learn

---

## 📊 Sample Output

- Price distribution plots for each crop
- Time series trend lines
- Linear regression forecast with MSE printed

---

## 📁 File Structure

