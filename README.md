# Hotel Booking Cancellation Prediction — Machine Learning Project

This project demonstrates a full **data science workflow** to predict whether a hotel booking will be canceled using real-world booking data. The pipeline includes **data cleaning, exploratory analysis, feature engineering, model training, and evaluation** — all designed to support operational decision-making in hospitality revenue management.

> This is not just a basic notebook — this reflects end-to-end predictive modelling practice with sound evaluation and real-world business framing.

## 🚀 Project Overview

- **Problem Statement**  
  Predict hotel booking cancellations to help hotels better **manage overbookings**, improve **revenue**, and reduce costs associated with late cancellations.

- **Business Impact**  
  A reliable cancellation predictor enables revenue managers and operations teams to *quantify risk*, *optimize occupancy planning*, and *improve profitability*.

- **Data Source**  
  Hotel booking datasets with reservation records across multiple hotels, including booking details, guest information, and cancellation flag.

## 📊 Dataset Summary

- Multi-year booking records (~100k+ rows)
- ~30+ features including:
  - `lead_time`, `arrival_date`, `market_segment`, `deposit_type`
  - guest counts, room type, previous cancellations
- Target variable: **`is_canceled`** (binary classification)

## 🧠 Key Technologies Used

| Layer | Tools & Libraries |
|------|------------------|
| Data Preparation | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | scikit-learn, XGBoost |
| Modelling Techniques | Random Forest, Gradient Boosting, SMOTE |

## 🔄 Workflow

1. **Data Collection & Cleaning**  
   - Handle missing values  
   - Type casting  
   - Encoding categorical features

2. **Exploratory Data Analysis (EDA)**  
   - Feature distributions  
   - Cancellation trends  
   - Correlation insights

3. **Feature Engineering**  
   - Date feature extraction (month, season)
   - Encoding categorical features (One-Hot / Label encoding)
   - Derived features (e.g., total nights, repeated guests)

4. **Modelling & Evaluation**  
   - Train/Test split  
   - Multiple baseline models  
   - Hyperparameter tuning  
   - Metrics: Accuracy, Precision/Recall, F1-Score

## 📌 Results

- Models demonstrate strong predictive performance.
- Feature importance provides business insights (e.g., **lead time**, **deposit type**, and **market segment** are strong cancellation indicators).

## 📁 Repository Structure
Hotel-booking-cancellation-project/
│
├── data/
│ ├── hotel_bookings.csv
│ └── data_dictionary.md
│
├── notebooks/
│ └── Hotel_Cancellation_Prediction.ipynb
│
├── reports/
│ └── EDA_visualizations.png
│
├── requirements.txt
├── README.md
└── LICENSE
