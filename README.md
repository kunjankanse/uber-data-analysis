# 🚖 Uber Data Analysis Project

## 📌 Project Overview
This project performs **end-to-end data analysis** on real-world Uber trip data using **Python** and **Pandas**, with **Seaborn** and **Matplotlib** for data visualization.  
The goal is to explore trip patterns, identify business insights, and present trends in ride usage.

The analysis includes **data cleaning, transformation, exploratory data analysis (EDA), and visualization**.

---

## 🛠️ Technologies & Libraries Used
- **Python**
- **Pandas** – Data cleaning & manipulation
- **NumPy** – Numerical operations
- **Matplotlib / Pyplot** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📂 Dataset Description
The dataset contains trip-level details such as:

| Column       | Description |
|--------------|-------------|
| `START_DATE` | Trip start date & time |
| `END_DATE`   | Trip end date & time |
| `CATEGORY`   | Trip category (Business / Personal) |
| `START`      | Starting city/location |
| `STOP`       | Destination city/location |
| `MILES`      | Trip distance in miles |
| `PURPOSE`    | Trip purpose (e.g., Meeting, Errand) |

---

## 🔍 Analysis Performed

### **1. Data Cleaning & Preparation**
- Loaded dataset and required libraries
- Converted column names to lowercase
- Fixed date-time formats for `start_date` and `end_date`
- Removed duplicates and handled missing values

### **2. Exploratory Data Analysis (EDA)**
- **Total Trips:** Count of all trips taken
- **Average Trip Distance:** Mean distance per trip
- **Most Frequent Routes:** Top city pairs `(START ➝ STOP)`
- **Most Common Purpose:** Excluding missing values
- **Monthly Trends:** Trips per month & busiest month
- **Trips by Category:** Business vs. Personal split
- **Average Trip Duration:** `(end_date - start_date)` in hours/minutes
- **Missing Purpose Percentage:** Share of trips without a purpose
- **Day-of-Week Patterns:** Which weekday has the highest trip volume
- **Distance by Purpose:** Total & average distance for each purpose
- **Time-of-Day Analysis:** Morning / Afternoon / Night trip patterns
- **Hourly Activity:** Most active hours of the day
- **Outlier Detection:** Extremely long durations or distances

---

## 📊 Key Insights
- **Busiest Month:** Identified based on trip count
- **Top Routes:** Frequent start–stop location pairs
- **Purpose Distribution:** Business trips dominate the dataset
- **Peak Hours:** Highest trip activity observed in morning commute hours
- **Outliers:** A small number of trips had unusually long distances or durations

---

## 🚀 How to Run
1. Clone the repository or download the `.ipynb` notebook.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
3. Place the dataset in the working directory.
4. Open and run the notebook: `UberDataAnalysis.ipynb`
