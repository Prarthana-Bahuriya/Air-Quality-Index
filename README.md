# Air-Quality-Index
# 🌬️ Air Quality Liverpool

## 📊 Project Overview
A data-driven project analyzing Liverpool's air quality patterns and their relationship with meteorological conditions. Using two years of hourly measurements, we developed a Random Forest model (R² = 0.804) that predicts Air Quality Index values based on pollutant concentrations and weather parameters. Our analysis reveals seasonal variations in air quality, with particulate matter (PM2.5, PM10) having the strongest impact on pollution levels, while wind speed shows a modest dispersal effect. This tool supports environmental planning and public health initiatives through accurate air quality forecasting.

## 🔍 What We Explored
- **Temporal Trends**: How air quality fluctuates hourly, daily, and seasonally
- **Weather Impact**: The relationship between temperature, wind speed, humidity and pollution
- **Pollutant Patterns**: Concentration variations of PM2.5, PM10, NO2, CO, SO2, and O3
- **Predictive Modeling**: Machine learning approach to forecast future AQI levels

## 💻 Methodology

### Data Collection & Preparation
- Merged API-sourced pollution data with meteorological measurements
- Implemented sophisticated data cleaning and feature engineering
- Applied KNN imputation to handle missing values
- Created temporal features for enhanced analysis

### Advanced Analytics
- Correlation analysis between weather parameters and pollution levels
- Time series decomposition of AQI patterns
- Statistical significance testing of environmental relationships
- Visual exploration through interactive plots and heatmaps

### Machine Learning
- **Algorithm**: Random Forest Regression
- **Performance**: R² = 0.804, MSE = 63.35
- **Feature Importance**: Identified key predictors of air quality changes

## 🔑 Key Insights

### Seasonal Patterns
❄️ **Winter**: Higher AQI levels (particularly January/December)  
☀️ **Summer**: Improved air quality with lower pollution readings

### Correlations
- 💨 Wind Speed (-0.15): Negative correlation with AQI, helping disperse pollutants
- 🌡️ Temperature (0.05): Minimal direct impact on overall air quality
- 💧 Humidity (0.02): Negligible correlation with AQI levels

### Pollutant Impact
- PM2.5 (0.95) and PM10 (0.81): Strongest correlation with AQI
- Particulate matter represents the most significant contributor to air quality degradation

## 👥 Our Team
- Arunesh Kumar Rai
- Anupam Semwal
- Prarthana Bahuriya

---

### 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

<p align="center">
  <i>Breathe better with better data</i>
</p>
