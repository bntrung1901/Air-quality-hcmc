# 🏙️ HCMC Air Quality Analysis (2021–2022)

This project analyzes the air quality in Ho Chi Minh City using real environmental and weather data from multiple monitoring stations over 2021 and the first half of 2022.

## 📌 Objectives

- Calculate AQI for multiple pollutants based on US EPA standards.
- Identify the main pollutant at each time point.
- Analyze air pollution trends by time (hour, season) and space (station).
- Visualize insights in an interactive Power BI dashboard.

## 🧮 Data Overview

- **Time Range**: January 2021 – June 2022  
- **Pollutants**: PM2.5, SO2, NO2, CO, O3, TSP  
- **Stations**: 6 monitoring stations across Ho Chi Minh City  
- **Weather Features**: Temperature, Humidity, Wind Speed, etc.

## 🔍 Methodology

- Cleaned and merged air quality and weather datasets using Python (pandas).
- Calculated AQI per hour per station per pollutant based on [US EPA breakpoints](https://www.airnow.gov/aqi/aqi-calculation/).
- Identified the main pollutant by selecting the pollutant with the highest AQI at each timestamp.
- Performed EDA by:
  - Hour of the day
  - Season
  - Monitoring Station
  - AQI level and pollutant distribution

## 📊 Dashboard (Power BI)

The final dashboard includes:

1. **Average AQI by Hour (Line Chart)**
2. **Average AQI by Season (Treemap Chart)**
3. **Average AQI by Station (Bar Chart)**
4. **Average AQI by Quater (Column Chart)**
5. **AQI Level Distribution (Donut Chart)**
6. **Main Pollutant Frequency (Pie Chart)**
7. **Interactive Filters (Slicers)** by Station, Season, Quater, Hour and Main Pollutant

➡️ [Download Power BI file (.pbix)](./Air Quality Dashboard - HCMC 2021–2022.pbix)

## 📈 Key Findings

- AQI peaked around **5 PM** (typically during rush hour).
- **SO2** was the most frequent main pollutant.
- **Winter and Spring** had higher pollution levels than Summer and Autumn.
- Station 1 reported the highest average AQI during the observed period.

## 🚀 Tools Used

- **Python** (Jupyter Notebook)
- **Pandas, Matplotlib, Seaborn**
- **Power BI** for dashboard visualization

## 📂 Folder Structure
📁 HCMC_Air_Quality_Analysis
│
├── data/ # Raw and cleaned data files
├── notebooks/ # Jupyter Notebooks for EDA and AQI calculation
├── HCMC_Air_Quality_Analysis_2021_2022.pbix # Power BI Dashboard
└── README.md # Project documentation


## 👤 Author

**[Trung Bui]** – Data Analyst  
📧 [bntrung1901@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/trung-bui-1020ba93/) | [GitHub](https://github.com/bntrung1901)
