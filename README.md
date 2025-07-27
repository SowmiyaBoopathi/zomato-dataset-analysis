# 🍽️ Zomato Bangalore Restaurants Data Analysis

This project involves a comprehensive data analysis and visualization of the Zomato Bangalore Restaurants dataset using Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

## 📁 Dataset

- Dataset Source: [Kaggle - Zomato Restaurants Bangalore](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
- Format: CSV
- Size: ~2 MB
- Rows: ~9,000+
- Columns: 17+

## 📊 Objectives

- Clean the dataset (handle null values, remove duplicates, format columns).
- Explore and visualize:
  - Popular restaurant chains in Bangalore
  - Online ordering and table booking trends
  - Top locations by number of restaurants
  - Cuisine types and food ratings
  - Relationship between ratings and votes
- Derive useful business insights for restaurant stakeholders.

## 🧹 Data Cleaning Steps

- Removed unnecessary columns (e.g., `url`, `phone`).
- Cleaned the `rate` column (converted to float).
- Handled null values in `dish_liked`, `rest_type`, and `location`.
- Dropped duplicate entries.

## 📈 Key Visualizations

- Bar plot of top restaurant types.
- Pie chart of online ordering availability.
- Count plots of locations with most restaurants.
- Joint plots to explore correlation between `rate` and `votes`.
- Heatmaps for correlation matrix.

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
