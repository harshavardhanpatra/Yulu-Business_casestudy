Here's a professional GitHub README you can directly paste into `README.md` for your project.

---

# 🚲 Yulu Business Case Study - Data Analytics Project

## 📌 Project Overview

This project analyzes Yulu's shared electric cycle rental dataset to identify the key factors affecting bike rental demand and provide data-driven business recommendations.

The analysis includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Univariate Analysis
* Bivariate Analysis
* Hypothesis Testing
* Business Insights & Recommendations

The goal is to help Yulu optimize fleet deployment, improve operational efficiency, and better understand customer rental behavior. 

---

# 🎯 Business Problem

Yulu is India's leading micro-mobility service provider offering electric bicycles for short-distance commuting.

The company wants to understand:

* What factors influence bike rental demand?
* Does season impact rentals?
* Does weather affect rentals?
* Do working days significantly change rental behavior?
* How can Yulu improve operational planning?

---

# 📂 Dataset Information

The dataset contains information about:

* Date & Time
* Season
* Weather Conditions
* Temperature
* Humidity
* Windspeed
* Working Day Indicator
* Holiday Indicator
* Number of Rentals

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

### Statistical Methods

* 2-Sample T-Test
* One-Way ANOVA
* Chi-Square Test

---

# 📊 Exploratory Data Analysis

## Univariate Analysis

Analyzed:

### Continuous Variables

* Temperature
* Humidity
* Windspeed
* Rental Count

### Categorical Variables

* Season
* Weather
* Working Day
* Holiday

---

## Bivariate Analysis

Studied relationships between:

* Rentals vs Season
* Rentals vs Weather
* Rentals vs Temperature
* Rentals vs Humidity
* Rentals vs Working Day

---

# 📈 Hypothesis Testing

## 1. Working Day vs Rentals

### Test Used

2-Sample Independent T-Test

### Result

* Test Statistic = 1.21
* p-value = 0.2264

### Decision

Fail to Reject H₀

### Insight

Working days do not significantly affect rental demand when analyzed at an aggregate level. 

---

## 2. Season vs Rentals

### Test Used

One-Way ANOVA

### Result

* F Statistic = 236.95
* p-value < 0.0001

### Decision

Reject H₀

### Insight

Rental demand differs significantly across seasons. 

---

## 3. Weather vs Rentals

### Test Used

One-Way ANOVA

### Result

* F Statistic = 65.53
* p-value < 0.0001

### Decision

Reject H₀

### Insight

Weather conditions significantly impact bike rental demand. 

---

## 4. Weather vs Season Dependency

### Test Used

Chi-Square Test of Independence

### Result

* Chi-Square Statistic = 49.16
* p-value < 0.0001

### Decision

Reject H₀

### Insight

Weather patterns are dependent on season. 

---

# 🔍 Key Findings

### Season Matters

Demand is highest during Summer and Fall.

### Weather Matters

Poor weather conditions reduce rentals significantly.

### Temperature is Important

Temperature showed the strongest positive relationship with demand.

### Humidity Impacts Usage

Higher humidity tends to suppress bike rentals.

### Peak Usage Hours

Highest demand occurs around:

* 8 AM
* 5 PM – 6 PM

These correspond to office commuting hours. 

---

# 💡 Business Recommendations

### 1. Seasonal Fleet Planning

Increase cycle availability during:

* Summer
* Fall

Reduce fleet allocation during low-demand seasons.

### 2. Weather-Aware Operations

Integrate weather forecasting APIs to:

* Predict demand
* Optimize fleet deployment

### 3. Temperature-Based Demand Forecasting

Use temperature forecasts as a major input for demand prediction models.

### 4. Humidity-Sensitive Marketing

Offer discounts and promotions during high-humidity periods.

### 5. Peak Hour Optimization

Ensure maximum cycle availability during:

* Morning commute hours
* Evening commute hours

### 6. Further Working-Day Analysis

Perform hourly-level analysis rather than aggregate-level analysis for working-day effects. 

---


---

# 🚀 Future Improvements

* Build a demand forecasting model
* Create interactive Power BI dashboards
* Develop seasonal demand prediction systems
* Deploy weather-aware rental recommendation engine
* Implement real-time fleet optimization

---

# 👨‍💻 Author

**Harshavardhan Patra**

Applied Data Science & Business Analytics Student

Skills:

* Python
* SQL
* Statistics
* Data Analysis
* Data Visualization
* Hypothesis Testing
* Exploratory Data Analysis (EDA)

---

⭐ If you found this project useful, consider giving it a star on GitHub!
