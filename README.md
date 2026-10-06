# 🚕 NYC Yellow Taxi – EDA Project using Python

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

Exploratory Data Analysis (EDA) on real-world **NYC Yellow Taxi trip data** using Python.
The goal is to clean the raw data, find patterns in trips and fares, and turn them into clear business insights.

---

## 🎯 Objectives

- Clean and preprocess raw trip data (missing values, duplicates, invalid records)
- Detect and handle outliers in fare and trip distance
- Analyse fare, distance and trip duration patterns
- Identify demand trends by hour, day and payment type
- Present findings with clear visualizations

---

## 📊 Dataset

| Detail | Info |
|--------|------|
| Source | NYC Taxi & Limousine Commission (TLC) Trip Record Data |
| Period | [month / year used] |
| Rows | [number of rows] |
| Key columns | pickup/dropoff time, trip_distance, fare_amount, tip_amount, payment_type, passenger_count |

---

## 🧹 Data Cleaning Steps

1. Removed duplicate records
2. Handled missing values: [how you handled them]
3. Removed invalid trips (zero or negative fare, zero distance)
4. Treated outliers using [IQR / capping / removal]
5. Created new columns: [trip duration, pickup hour, day of week, etc.]

---

## 🔍 Key Insights

> Notebook se apne asli findings yahan likho. Example format:

1. **Peak demand:** Most trips happen between [X] and [X] hours.
2. **Fare vs distance:** Average fare is $[X] for an average distance of [X] miles.
3. **Payment type:** [X]% of trips are paid by credit card.
4. **Outliers:** [X]% of records had unusual fares or distances and were treated.

---

## 📈 Visualizations

<!-- Notebook ke 2-3 best charts ko repo me "images" folder me upload karo, phir ye lines use karo -->

![Trips by Hour](images/trips_by_hour.png)
![Fare vs Distance](images/fare_vs_distance.png)

---

## 🛠️ Tools Used

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

---

## 📁 Project Structure

```
├── NYC_Taxi_EDA.ipynb    # Main analysis notebook
├── images/               # Chart screenshots
├── LICENSE
└── README.md
```

---

## ▶️ How to Run

```bash
git clone https://github.com/parastomar610-pixel/EDA-Project-using-Python-NYC-Yellow-Taxi-Real-World-Data.git
cd EDA-Project-using-Python-NYC-Yellow-Taxi-Real-World-Data
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

---

## 👤 Author

**Paras Tomar** – MIS Executive | Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/paras-tomar-165364186/) · 📧 parastomar610@gmail.com
