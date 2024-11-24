# Weather-Dashboard-using-Grafana

Acknowledgement for the Dataset - [Mr. Muthukumar.J](https://www.kaggle.com/datasets/muthuj7/weather-dataset)

**Project Made by :**

**Agathiyan K (045005)**

**Mohit Vaidya (045032)**

**Shantanu Bharvirkar (045055)**

## About the Dataset

The dataset consists of **96,453 entries** and **12 variables**, offering a comprehensive overview of weather conditions. Below is an explanation of each variable:

1. **FormattedDate**: Timestamps of hourly weather observations.
2. **Summary**: A short description of the weather (e.g., "Partly Cloudy").
3. **PrecipType**: The type of precipitation (rain, snow, or none). Some entries have missing values.
4. **TemperatureC**: Measured air temperature in degrees Celsius.
5. **ApparentTemperatureC**: "Feels-like" temperature considering wind and humidity effects.
6. **Humidity**: Relative humidity as a decimal (0-1).
7. **WindSpeedkmh**: Wind speed measured in kilometers per hour.
8. **WindBearing**: Wind direction in degrees (0-360).
9. **Visibilitykm**: Visibility distance in kilometers.
10. **LoudCover**: Always 0, offering no actionable information.
11. **PressureMillibars**: Atmospheric pressure in millibars.
12. **DailySummary**: Narrative describing daily weather conditions.

## Objectives

1. Investigate correlations between precipitation types (rain, snow) and wind speed.
2. Analyze the relationship between temperature, precipitation type, and apparent temperature.
3. Explore wind speed and bearing distributions to understand prevailing patterns.
4. Examine daily average temperature trends and seasonal variations.
5. Study pressure fluctuations and their role in weather forecasting.
6. Evaluate humidity trends and their association with weather summaries and precipitation events.
7. Assess visibility trends under varying weather conditions.
8. Provide actionable managerial insights for logistics, energy, agriculture, and urban planning.

## Dashboard

https://drive.google.com/drive/folders/16YUKeXr_W8vODRg5aN-OaF0VKKN5me5K

![WhatsApp Image 2024-11-24 at 22 24 14_f556b062](https://github.com/user-attachments/assets/fcf6471e-d239-4e3b-8ca5-2e8dc6b3b311)
![WhatsApp Image 2024-11-24 at 22 32 13_8ef7a50e](https://github.com/user-attachments/assets/0db80170-66bb-42d4-a555-8ce84eadaa75)


## Insights from Graphs

1. **Precipitation Type vs Wind Speed**:
   - **Rain**: Average wind speed during rain is around 9.34 km/h, with higher variability during storms.
   - **Snow**: Wind speeds are generally lower, indicating atmospheric stability during colder conditions.
   - **No Precipitation**: Displays a broader wind speed range, from calm conditions to gusty clear days.

2. **Average Temperature by Precipitation Type**:
   - **Rainy Conditions**: Average temperature is 12.6°C, indicating mild to warm rain patterns.
   - **Snowy Conditions**: Temperatures are below freezing (generally <0°C).
   - **No Precipitation**: Temperatures range widely, from sub-zero winter lows to summer highs.

3. **Wind Speed Distribution**:
   - Wind speeds mostly cluster around 34 km/h, indicating frequent breezy conditions.
   - Extreme winds (>50 km/h) are rare but could signal storms.
   - Calm days (<10 km/h) reflect stagnant weather patterns.

4. **Wind Bearing Distribution**:
   - Winds predominantly come from specific directions (e.g., NW or SW), revealing regional wind patterns.
   - Rare wind directions may indicate topographical influences.
   - Seasonal variations in wind direction clustering are evident.

5. **Temperature by Precipitation Type**:
   - **Rain**: Occurs in 10-20°C, consistent with temperate or tropical rains.
   - **Snow**: Is only observed below 0°C.
   - **No Precipitation**: Displays extreme variations, including sub-zero nights and hot summer days.

6. **Daily Average Temperature**:
   - Average daily temperature (~22.7°C) indicates moderate, comfortable weather.
   - Seasonal trends: Peaks in summer, lows in winter, with abrupt changes suggesting cold fronts or heatwaves.

7. **Humidity Comparison by Weather Summary**:
   - **Cloudy Weather**: Humidity levels exceed 80% for "Mostly Cloudy" and "Overcast."
   - **Clear Weather**: Lower humidity (~50-60%) correlates with sunny days.
   - **Foggy Conditions**: Peak humidity (~100%) reflects condensation or saturated air.

8. **Temperature vs Apparent Temperature Comparison**:
   - Differences are more pronounced on windy or humid days, reflecting wind chill and heat index effects.
   - Calm days show alignment between actual and apparent temperatures.
   - Apparent temperature drops below actual during windy, cold conditions and exceeds actual in humid, warm weather.

9. **Humidity Trend**:
   - Humidity increases during precipitation or overcast periods.
   - Daily cycles show peaks at night/early morning and drops during warm afternoons.
   - Seasonal patterns indicate higher humidity during rainy seasons or winter.

10. **Pressure Trend**:
    - Stable pressure reflects calm weather.
    - Falling pressure precedes rain or storms, signaling instability.
    - Rising pressure indicates clearing skies or dry weather.

11. **Temperature Trend**:
    - Clear seasonal cycles: Higher in summer and lower in winter.
    - Daytime peaks and nighttime cooling are evident.
    - Fluctuations align with cold fronts or heatwaves.

12. **Wind Speed and Bearing by Summary**:
    - **Cloudy Weather**: Moderate wind speeds align with storm systems.
    - **Clear Weather**: Calmer, more variable winds.
    - **Stormy Conditions**: Stronger winds with distinct prevailing directions.

13. **Average Temperature by Wind Speed**:
    - Calm winds (<10 km/h) show broad temperature ranges due to stagnant air.
    - Moderate winds (~20-30 km/h) align with mild, stable conditions.
    - High wind speeds correlate with extreme temperatures, enhancing cooling or heating effects.

14. **Average Pressure by Weather Summary**:
    - **Clear Weather**: High-pressure systems dominate (>1015 mb).
    - **Partly Cloudy**: Slightly lower pressure suggests transitional weather.
    - **Mostly Cloudy**: Lower pressure (~1010 mb) signals precipitation likelihood.


## Managerial Insights

1. **Logistics Operations**:
   - Avoid scheduling transportation during high wind speeds and low visibility periods, particularly during precipitation events.

2. **Energy Management**:
   - Prepare for increased heating/cooling demands during extreme apparent temperatures caused by high winds or humidity.

3. **Disaster Preparedness**:
   - Monitor rapid drops in atmospheric pressure to anticipate storms or other severe weather events.

4. **Outdoor Event Planning**:
   - Schedule events on days with stable atmospheric pressure, low wind speeds, and clear skies.

5. **Agricultural Planning**:
   - Use humidity and precipitation trends to optimize irrigation schedules and prevent water wastage during rainy or humid periods.

6. **Retail Forecasting**:
   - Stock seasonal products like umbrellas, snow gear, and fans based on precipitation and temperature trends.

7. **Urban Infrastructure**:
   - Use wind direction and speed data to design wind-resistant structures and optimize street layouts for pedestrian safety.

8. **Tourism Strategy**:
   - Promote tourism activities during periods of clear skies and comfortable temperatures (e.g., 20-25°C with low winds).

9. **Health Precautions**:
   - Issue warnings for extreme apparent temperatures, particularly for outdoor workers in high wind or humid conditions.

10. **Supply Chain Management**:
    - Prepare inventory and logistics for potential disruptions caused by severe weather, especially during storms or precipitation events.


## Summary and Conclusion

The dashboard analysis highlights intricate weather patterns, including temperature, wind speed, humidity, and precipitation relationships. Key findings include:
- Rain aligns with higher wind speeds and moderate temperatures.
- Snow occurs in sub-zero temperatures with calmer winds.
- Visibility and pressure trends act as reliable indicators for upcoming weather changes.

By leveraging these insights, stakeholders can enhance operational efficiency, optimize resource planning, and mitigate weather-related risks. This data-driven approach ensures better decision-making across multiple sectors, including logistics, energy, agriculture, and urban planning.
