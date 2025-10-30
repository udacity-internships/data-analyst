# Communicate Data Findings

**Project by:** Yazan Al-Sedih  
**Date:** 2025-10-30  
**Language:** Python (Pandas, Seaborn, Matplotlib, Jupyter Notebook)

---

## Project Overview

This project demonstrates the importance of data visualization in analyzing and communicating data findings.  
The dataset used is **Ford GoBike Data Analysis**, which contains bike-sharing trip information.

The project has two main parts:

1. **Exploratory Data Visualization:**

   - Systematically exploring the dataset
   - Analyzing single variables, relationships between variables, and multi-variable patterns
   - Generating insights from the raw data

2. **Explanatory Data Visualization:**
   - Creating clear visualizations to communicate findings effectively
   - Highlighting key trends, patterns, and business insights

---

## Dataset

- **Name:** Ford GoBike Data Analysis
- **Source:** Ford GoBike System
- **Cleaned data size:** 183,340 trips
- **Key features:**
  - Trip duration, start and end times
  - User type (Subscriber or Customer)
  - Gender, age
  - Start and end stations
  - Derived features like start hour, day of the week, etc.

---

## Key Findings

### User Type

- **Subscribers dominate usage:** 89.2% of trips
- **Customers:** 10.8% of trips
- **Insight:** Subscribers mostly use bikes for commuting; Customers for leisure

### Trip Duration

- Median trip duration:
  - Subscribers: 490 seconds (~8 minutes)
  - Customers: 792 seconds (~13 minutes)
- Outliers exist; pricing and fleet management can consider these patterns

### Trips by Hour

- **Subscribers:** Peaks at 8 AM and 5 PM
- **Customers:** Even distribution throughout the day
- **Insight:** Allocate bikes to high-demand hours, target leisure users during off-peak

### Additional Insights

- Gender and age affect trip patterns
- Some stations have higher usage, useful for maintenance and expansion planning

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Project Structure

```plaintext
├── Communicate_Data_Findings_EDA.ipynb       # Exploratory Data Analysis
├── Communicate_Data_Findings_Visuals.ipynb  # Explanatory Visualizations
├── data/
│   └── ford_gobike_clean.csv                # Cleaned dataset
└── README.md                                # Project documentation

```
