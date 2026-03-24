# 🏃‍♂️ FitBit Health & Sleep Predictor (AI/ML)

An end-to-end data science project using Python to analyze how daily activity affects sleep quality.

## 📌 Project Overview
This project processes raw data from the **Fitabase** dataset to identify patterns between physical exertion and nocturnal recovery. By merging activity and sleep logs, I built a **Linear Regression model** to predict sleep duration based on daily habits.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Platform:** Google Colab

## 📊 Key Features
* **Data Cleaning:** Removed duplicates and formatted time-series data for analysis.
* **Feature Engineering:** Created a **Sleep Efficiency** metric ($TotalMinutesAsleep / TotalTimeInBed$).
* **Relational Merging:** Linked activity and sleep datasets using User ID and Date keys.
* **Predictive Modeling:** Developed a model to forecast sleep minutes using Steps and Active Minutes as inputs.

## 📈 Insights
* **Heatmap Analysis:** Visualized correlations between sedentary time and sleep quality.
* **Predictive Tool:** Includes a function to input custom activity data and receive an AI-generated sleep forecast.

---
*Created as part of an AIML Portfolio project.*
