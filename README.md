# 📊 Sales Insights & Forecasting Analysis

This project is a comprehensive exploratory data analysis (EDA) and visualization of a retail sales dataset. The goal is to clean, transform, and analyze sales data to uncover key business insights that can help in strategic decision-making.

## 📦 Dataset

The dataset used in this project is sourced from Kaggle:
[Rohit Sahoo - Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

It contains information about customer orders, including order dates, shipping dates, product categories, regions, segments, and sales figures.

## 🧰 Technologies & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Kaggle API

## 📌 Key Steps & Highlights

### ✅ 1. Data Loading
- Dataset is downloaded using the Kaggle API and extracted in Colab.
- Initial inspection with `.head()`, `.info()`, and `.describe()`.

### 🧹 2. Data Cleaning
- Missing postal codes filled using a valid value from Google search.
- Duplicate records checked.
- Order Date and Ship Date converted to datetime format.
- Extracted day, month, and year from both dates for time-based analysis.

### 📊 3. Data Exploration
- Value counts and aggregations based on:
  - **Ship Mode**
  - **Segment**
  - **Category**
  - **Region**
  - **Sub-Category**
- Trend analysis on **total sales over years**.
- Top 10 sales by **State and Shipping Month**.

### 🎨 4. Data Visualization
- Bar charts for segment and ship mode analysis.
- Pie chart showing sales by category.
- Count plots for regions and sub-categories.
- Line chart of sales trends over time.
- Scatter and boxen plots to understand distribution and relationships.

## 📈 Insights

- Identified the best-performing shipping modes and customer segments.
- Visualized sales trends across time and product categories.
- Highlighted sales concentration among states and product sub-categories.

## 🚀 How to Use

1. Open the project in Google Colab.
2. Upload your `kaggle.json` for API access.
3. Run all cells to download the dataset, clean the data, and view the visualizations.

---

## 🧠 Future Improvements

- Incorporate forecasting models (e.g., ARIMA, Prophet).
- Add profit and discount analysis.
- Build a dashboard using Streamlit or Power BI.

## 🧑‍💻 Author
- Ayman Mahmoud
- 📧 ayman.anaylst@gmail.com
- 📍 Giza, Egypt
- 🔗 LinkedIn Profile (https://www.linkedin.com/in/ayman-mahmoud-8b2287235/));
