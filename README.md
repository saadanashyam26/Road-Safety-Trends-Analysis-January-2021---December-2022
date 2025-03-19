

# Road Safety Trends Analysis: January 2021 - December 2022

## Overview
This project analyzes road accident data from January 2021 to December 2022 to uncover trends, patterns, and factors influencing road safety. The analysis includes temporal trends, geographic hotspots, and the impact of variables such as weather conditions, road surface conditions, and junction control types on accident severity and frequency. The goal is to provide actionable insights to improve road safety and reduce accidents.

---

## Dataset
The dataset used in this project was sourced from **Kaggle** and contains 300,000 records of road accidents. Each record includes variables such as:

- **Accident Date**
- **Day of Week**
- **Junction Control**
- **Accident Severity**
- **Weather Conditions**
- **Road Surface Conditions**
- **Number of Casualties**
- **Number of Vehicles**
- **Speed Limit**
- **Urban or Rural Area**
- **Vehicle Type**

[Dataset Link](https://www.kaggle.com/datasets/mabelhsu/api-clean-top-1000-youtubers-statistics)

---

## Project Objectives
The primary objectives of this project are:
1. **Identify Temporal Trends**: Analyze seasonal variations and long-term changes in accident occurrences.
2. **Geographic Hotspots**: Identify areas with disproportionately high accident rates.
3. **Risk Factors**: Investigate the impact of weather, road conditions, and junction types on accident severity.
4. **Vehicle and Speed Analysis**: Explore the relationship between vehicle types, speed limits, and accident severity.
5. **Policy Recommendations**: Provide data-driven recommendations to improve road safety.

---

## Key Visualizations and Insights

### 1. **Accident Severity by Day of the Week**
- **Insight**: Fridays have the highest number of slight and serious accidents, while Saturdays have the highest number of fatal accidents.
- **Visualization**: Bar chart showing the distribution of accident severity across days of the week.

### 2. **Speed Limit vs. Accident Severity in Urban and Rural Areas**
- **Insight**: Fatal accidents in rural areas are most common at 60-70 mph, while in urban areas, they occur at 30 mph.
- **Visualization**: Area graph comparing speed limits and accident severity in urban vs. rural areas.

### 3. **Time Series Analysis of Accidents**
- **Insight**: The number of accidents peaked in November for both 2021 and 2022, followed by a steep decline in December.
- **Visualization**: Line graph showing the trend of accidents over time.

### 4. **Geographic Distribution of Accidents**
- **Insight**: England has the highest number of accidents across all severity types, while Northern Ireland reported no fatal accidents.
- **Visualization**: Symbol map showing accident hotspots across local authority districts.

### 5. **Weather and Road Surface Conditions**
- **Insight**: "Wet or damp" road conditions combined with "Fine no high winds" resulted in the highest number of casualties (36,047).
- **Visualization**: Heatmap showing the relationship between weather conditions, road surfaces, and casualties.

---

## Tools and Technologies
- **Programming Languages**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Visualization Tools**: Tableau
- **Statistical Analysis**: Excel
- **Data Cleaning and Preparation**: Python, Excel

---



## Key Findings
1. **Temporal Trends**: Accidents peaked in November and declined in December for both years.
2. **Geographic Hotspots**: England had the highest number of accidents, with specific districts like Westminster and Birmingham being high-risk areas.
3. **Risk Factors**: Wet road conditions and uncontrolled junctions were significant contributors to severe accidents.
4. **Speed Limits**: Higher speed limits in rural areas correlated with more fatal accidents.
5. **Weather Impact**: Adverse weather conditions like snow and fog resulted in fewer accidents, likely due to reduced traffic.

---

## Future Enhancements
- **Advanced Predictive Modeling**: Use machine learning to predict accident likelihood based on historical data.
- **Real-Time Monitoring**: Develop a real-time dashboard for monitoring road safety metrics.
- **Demographic Analysis**: Include age and gender data to understand demographic-specific risk factors.
- **Policy Simulation**: Simulate the impact of proposed road safety interventions.

---


## References
1. Elvik, R., Hoye, A., Vaa, T., & Sorensen, M. (2009). *The Handbook of Road Safety Measures*. Emerald Group Publishing.
2. World Health Organization (WHO). (2021). *Road Traffic Injuries*. Retrieved from [WHO Road Safety](https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries).
3. Xie, Y., Liu, C., Wang, J., & Li, J. (2020). *A Data-Driven Approach for Visualizing Road Traffic Accidents Using Geographic Information Systems*. Safety Science, 131, 104903.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

