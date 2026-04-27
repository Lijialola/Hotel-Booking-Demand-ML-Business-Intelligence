# 🏨 Hotel Booking Demand: Data Analysis & Cancelation Prediction

## 📌 Project Overview
This end-to-end project analyzes over 117,000 hotel bookings to uncover the root causes of cancellations and develops a Machine Learning predictive model to empower proactive decision-making and safe overbooking strategies.

## 🛠️ Tech Stack
* **Data Cleaning & Analysis:** Python (Pandas, Matplotlib, Seaborn)
* **Machine Learning:** Scikit-Learn (Random Forest, Logistic Regression, GridSearchCV)
* **Business Intelligence:** Power BI, DAX

## 📊 Key Business Insights
1. **The Revenue Leak:** The global cancellation rate sits at 37.6%, representing a potential loss of €17M (Lost Revenue).
2. **The Loyalty Shield:** Repeated guests have a cancellation rate of only 16.2%, compared to 38.2% for new guests.
3. **The "Non-Refund" Anomaly:** 99.4% of bookings with a "Non-Refundable" deposit were canceled, indicating a critical payment gateway flaw or systematic fraud.

## 🤖 Machine Learning Model
A **Random Forest Classifier** was developed to predict the likelihood of a customer canceling their booking.
* **Accuracy:** 86.7%
* **Key Predictive Features (Feature Importance):** Lead Time, Deposit Type, and Average Daily Rate (ADR).
* **Business Value:** The model allows the hotel to score the cancellation risk of every new booking in real-time, moving from reactive reporting to proactive retention and scientific inventory management.

## 📂 Repository Structure
* `notebooks/`: Contains the Jupyter Notebook with the ETL process, EDA, and Machine Learning pipeline.
* `reports/`: Contains the final comprehensive Business Report (PDF) detailing the BI architecture and strategic recommendations.
