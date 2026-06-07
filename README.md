# 🔥 Algerian Forest Fires Analysis

## 📌 Project Overview

This project explores the Algerian Forest Fires Dataset to understand how weather conditions and fire weather indices relate to wildfire occurrence.

The analysis includes:

* Data Cleaning
* Missing Value Handling
* Data Type Conversion
* Exploratory Data Analysis (EDA)
* Regional Analysis
* Fire Risk Indicator Investigation

---

## 📊 Dataset Information

The dataset contains meteorological observations collected from two regions in Algeria.

Features include:

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rainfall
* FFMC (Fine Fuel Moisture Code)
* DMC (Duff Moisture Code)
* DC (Drought Code)
* ISI (Initial Spread Index)
* BUI (Build Up Index)
* FWI (Fire Weather Index)

Target Variable:

* Classes (Fire / Not Fire)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Data Cleaning Steps

The following preprocessing tasks were performed:

* Removed invalid records
* Handled missing values
* Reset indices
* Converted numerical columns to proper data types
* Standardized column names
* Added regional identifiers

---

## 📈 Key Insights

* Higher temperatures tend to be associated with increased fire activity.
* Low rainfall periods show elevated fire risk.
* Fire Weather Index (FWI) is strongly related to fire occurrence.
* Regional differences can be observed in weather patterns and fire behavior.

---

## 🚀 How to Run

```bash
git clone https://github.com/USERNAME/algerian-forest-fires-analysis.git

cd algerian-forest-fires-analysis

pip install -r requirements.txt

jupyter notebook
```

---

## 🎯 Future Improvements

* Fire Prediction Models
* Logistic Regression
* Random Forest Classification
* Feature Importance Analysis
* Wildfire Risk Prediction Dashboard
