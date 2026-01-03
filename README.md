# 🚗 Car Sales Dataset Exploration & Business Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![Dataset](https://img.shields.io/badge/Dataset-Car_Sales-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📘 About the Project

This project focuses on analyzing a **car dealership’s sales ecosystem** using **Python-based data analysis**.  
It covers:
- Vehicle inventory 🚘
- Customer demographics 👥
- Sales transactions 💰

The objective is to extract **actionable business insights** by exploring sales trends, customer behavior, and inventory performance.

---

## 🌍 Project Context

The dataset represents a **real-world car dealership scenario** operating between **2022 and 2025**.  
It captures end-to-end business operations such as:

- Vehicle availability and pricing  
- Customer purchase behavior  
- Revenue trends over time  
- Payment preferences  
- Salesperson performance  

All analysis is performed using **Python and data analysis libraries**.

---

## 📚 Dataset Overview

The project uses **three interconnected CSV files**, forming a relational structure:

| File Name | Description |
|----------|-------------|
| `Cars.csv` | Vehicle inventory and specifications |
| `Customers.csv` | Customer demographic information |
| `Sales.csv` | Transaction-level sales data |

---

## 🧾 Feature Descriptions

### 🚘 **Cars.csv**
| Feature | Description |
|--------|-------------|
| Car_ID | Unique identifier for each car |
| Brand | Car brand (Toyota, Tesla, BMW, etc.) |
| Model | Model name |
| Year | Manufacturing year (2015–2025) |
| Color | Vehicle color |
| Engine_Type | Petrol, Diesel, Electric, Hybrid |
| Transmission | Automatic / Manual |
| Price | Listed price of the car |
| Quantity_In_Stock | Units available |
| Status | Available / Reserved / Sold |

---

### 👥 **Customers.csv**
| Feature | Description |
|--------|-------------|
| Customer_ID | Unique customer identifier |
| Name | Customer name |
| Gender | Male / Female |
| Age | Customer age (18–70) |
| Phone | Contact number |
| Email | Email address |
| City | City of residence |

---

### 💰 **Sales.csv**
| Feature | Description |
|--------|-------------|
| Sale_ID | Unique transaction ID |
| Customer_ID | Linked customer ID |
| Car_ID | Linked car ID |
| Sale_Date | Date of purchase |
| Quantity | Number of cars purchased |
| Sale_Price | Final sale amount |
| Payment_Method | Cash / Credit / Installment |
| Salesperson | Sales executive handling the sale |

---

## 🔗 Dataset Relationships

- **Customers ↔ Sales** via `Customer_ID`
- **Cars ↔ Sales** via `Car_ID`

These relationships enable **multi-dimensional analysis** using Python.

---

## 🧹 Data Cleaning & Preprocessing

```python
print("Data Cleaning & Preprocessing Pipeline")
