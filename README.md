# Used Car Price Analysis — Practical Assignment 11.1

This repository contains my implementation of **"What Drives the Price of a Car?"**, following the **CRISP-DM** data science framework. The goal of the project is to determine which vehicle attributes most influence used car prices and to provide insights that help dealerships fine tune inventory decisions.

---

## Project Overview

A used car dealership wants to understand why certain vehicles sell for more than others. Using a dataset of about 426,000 used cars, I examined relationships between price and key features such as mileage, condition, year, manufacturer, and fuel type. The project includes data understanding, preparation, modeling, and interpretation of results.

---

## Notebook

You can view the full Jupyter notebook here:

prompt_II_nicolini_v1.ipynb

---

## Summary of Findings

Key insights from the analysis:

- **Mileage (odometer) is one of the strongest negative predictors of price.** Cars with higher mileage consistently sell for less.
- **Condition significantly impacts value.** Cars rated “good,” “like new,” or “new” command higher prices.
- **Newer model years sell for more**, which is consistent with expected depreciation patterns.
- **Price distribution is heavily right skewed**, with most used cars priced below \$20,000 and a small number of very expensive outliers.
- **Linear and Ridge regression models performed similarly**, both achieving:
  - RMSE ≈ **7,090**
  - MAE ≈ **4,879**
  - R² ≈ **0.699**, so the model explains roughly 70 percent of the variance in price.

These insights can help dealerships make more informed decisions about which vehicles retain value and how to structure their inventory.

---
