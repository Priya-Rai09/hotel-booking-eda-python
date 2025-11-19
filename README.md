## **Hotel Booking EDA in Python**

A complete exploratory data analysis project on hotel booking data to understand booking patterns, customer behavior, cancellation trends, seasonality, and factors influencing hotel demand.

---

## 📑 **Table of Contents**

1. [Project Overview](#project-overview)
2. [Project Structure](#project-structure)
3. [Key Analysis Performed](#key-analysis-performed)
4. [Technologies Used](#technologies-used)
5. [Key Insights](#key-insights)
6. [How to Run](#how-to-run)
7. [Requirements](#requirements)

---

## 📌 **Project Overview**

This project performs **Exploratory Data Analysis (EDA)** on a Hotel Booking dataset using Python.
The objective is to uncover insights related to:

* Booking cancellations
* Seasonal booking trends
* Customer segments
* Lead time behavior
* ADR (pricing) patterns
* Factors affecting hotel demand

---

## 📂 **Project Structure**

```
hotel-booking-eda-python/
│
├── data/
│   ├── hotel_booking.csv
│
├── notebooks/
│   ├── hotel_booking_eda.ipynb
│
├── images/
│   ├── correlations.png
│   ├── cancellations.png
│   ├── booking_trends.png
│
├── README.md
│
└── requirements.txt
```

---

## 📊 **Key Analysis Performed**

* Data cleaning & preprocessing
* Missing value treatment
* Univariate analysis (distribution plots, countplots)
* Bivariate analysis (correlation heatmap, scatter plots)
* Cancellation pattern analysis
* Seasonal trend analysis
* Customer type behavior
* Lead time distribution
* ADR (Average Daily Rate) analysis

---

## 🛠️ **Technologies Used**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 **Key Insights**

* City hotels show **higher cancellation rates** than resort hotels.
* **Longer lead time increases cancellation probability.**
* Summer months experience **peak bookings**.
* **Repeat guests** tend to cancel less frequently.
* ADR varies significantly between hotel types.

---

## ▶ **How to Run**

1. Clone the repository

   ```
   git clone https://github.com/yourusername/hotel-booking-eda-python.git
   ```
2. Install dependencies

   ```
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook

   ```
   jupyter notebook
   ```

---

## 📎 **Requirements**

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---


