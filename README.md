# 🍔 Food Delivery Data Cleaning & Analysis

## 📌 Project Overview

This project focuses on **data cleaning, exploratory data analysis (EDA), and reporting automation** using a food delivery dataset.

The main objective is to clean raw food delivery data, handle missing and inconsistent values, convert data into appropriate formats, analyze delivery patterns, and create meaningful visualizations.

---

## 🎯 Objectives

- Clean and preprocess the raw dataset
- Handle missing values
- Standardize inconsistent text values
- Convert columns into appropriate data types
- Check and remove duplicate records
- Perform exploratory data analysis
- Analyze factors affecting delivery time
- Generate visualizations
- Export the cleaned dataset and summary report

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **Git & GitHub**

---

## 📊 Dataset Information

The dataset contains information about food delivery orders, delivery partners, restaurants, weather, traffic, vehicles, and delivery time.

### Dataset Statistics

| Metric | Value |
|---|---:|
| Total Records | 45,593 |
| Total Columns | 20 |
| Missing Values After Cleaning | 0 |
| Duplicate Records | 0 |
| Average Delivery Time | 26.29 minutes |
| Average Delivery Person Age | 29.58 years |
| Average Delivery Rating | 4.64 |

### Important Columns

- `Delivery_person_ID`
- `Delivery_person_Age`
- `Delivery_person_Ratings`
- `Restaurant_latitude`
- `Restaurant_longitude`
- `Delivery_location_latitude`
- `Delivery_location_longitude`
- `Order_Date`
- `Time_Orderd`
- `Time_Order_picked`
- `Weatherconditions`
- `Road_traffic_density`
- `Vehicle_condition`
- `Type_of_order`
- `Type_of_vehicle`
- `multiple_deliveries`
- `Festival`
- `City`
- `Time_taken(min)`

---

# 🧹 Data Cleaning Process

## 1. Data Loading

The raw CSV dataset was loaded using Pandas.

```python
train = pd.read_csv("train.csv")
