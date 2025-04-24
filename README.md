# Omdena Smart Agriculture Using AI in Kano, Nigeria

Omdena is a collaborative AI platform where data science and machine learning professionals can volunteer to work on projects in collaboration with startups, SMEs, NGOs and governments. Projects are focused on delivering data-driven technological solutions that drive positive social, environmental and economic impact.

Project Link: https://www.omdena.com/chapter-challenges/smart-farming-using-ai-for-sustainable-agriculture-in-kano-state-nigeria 

Project Repo: https://github.com/OmdenaAI/KanoNigeriaChapter_SmartFarming

<br>

<img width="800" alt="Screenshot 2025-03-28 at 10 27 00 PM" src="https://github.com/user-attachments/assets/b6a41b9c-c507-441b-bef8-30ab6b57ec4c" />


<br>
<br>
During the project, I was a key contributor to the following tasks:

1. Research and Data Collection
   
2. Data Preprocessing and Exploratory Data Analysis

3. Model Development - Historical Data Analysis and Forecasting

<br>

SUMMARY:
- Collaborated on an AI for Smart Agriculture project with Omdena, working with 50+ professionals from 7+ countries on data collection, cleaning, EDA, visualisation & statistical modelling.
- Spearheaded research and collection of soil and weather data from 37 LGAs (Local Govt Areas) in North, South and Metropolitan Kano - spanning 11 years, 12 metrics and totalling ~1.8 million data points.
- Identified optimal planting windows for local farmers based on soil moisture, rainfall patterns, and other weather metrics.
- Developed interpretive charts and region-specific insights based on statistical models of soil moisture and rolling window rainfall patterns. This analysis informed a planting readiness framework with the potential to improve planting outcomes across 1,000+ hectares - thereby reducing crop loss due to mis-timed sowing in Nigerian Local Government Areas and positively impacting more than 1 million Nigerian farmers.
- Created farmer-facing recommendations and visualisations, contributing to actionable and data-backed agricultural guidance to be used by local stakeholders.
- Time series forecasting - implemented Holt-Winters Smoothing for time series analysis; used rolling forecasts for predicting temperature and soil moisture with R-Squared > 0.85 and sMAPE < 12%. Evaluated models using MAE, RMSE, sMAPE, R-Squared and improved model performance by >60%.
- Findings and visuals to be integrated into project outputs shared with local agriculture experts and community partners.

<img width="800" alt="Screenshot 2025-03-28 at 10 26 34 PM" src="https://github.com/user-attachments/assets/9d8fd580-f23e-4391-b291-d77f512759bc" />

<br>
<br>
<br>

***Bridging Local Wisdom and Data: Enhancing Planting Frameworks in Kano, Nigeria***

The current planting framework in Kano is largely shaped by farmers’ traditional knowledge and observations of rainfall onset. While these practices are deeply rooted and widely trusted, they can be vulnerable to the increasing unpredictability of rainfall patterns and climate variability.
Through this project, I collaborated with Omdena's Kano Chapter to develop a data-informed approach that complements and strengthens this existing system. Drawing on 11 years of historical data on rainfall, soil moisture, temperature, and wind speed, I identified patterns and thresholds that align with farmer observations - but add precision and consistency.

Key contributions include:

•	Soil Moisture-Based Planting Readiness - Farmers traditionally dig to check for soil moisture; I helped operationalise this using Surface Soil Wetness data (upper 5-10 cm), introducing a planting threshold of 0.3–0.5 (as recommended by local experts), validated against crop-specific moisture needs. This approach, combined with root and profile soil moisture data, offers a more stable signal than rainfall alone, helping reduce the risk of premature planting and replanting.

•	Localised Rainfall Classification - Rain categories were defined in locally understood terms (e.g., Ruwan Yayyafi, Ruwan Tsakiya), bridging the gap between meteorological data and farmer intuition. These were mapped using a 10-day rolling rainfall window, helping identify meaningful rain patterns that give the average expected rainfall while also accounting for the possibility of deviations (such as unusually heave showers) based on historical evidence.

•	Planting Readiness Index (PRI) - In collaboration with local domain experts, I helped inform a five-stage PRI framework (Not Ready → Watch → Prepare → Plant → Caution), integrating soil moisture and rainfall into a simple, interpretable scale for farmers.

•	Farmer-Facing Visualisations - By combining climate trends with infographics and annotated charts, I translated complex data into tools that can be used in training, advisory apps, or simple seasonal guides.

Potential Impact:
This framework supports more confident, timely planting decisions and could ***improve outcomes across thousands of hectares, and impact more than a million Nigerian farmers annually*** if implemented effectively. It can be integrated into existing agricultural training programs, or serve as the foundation for localised, data-driven advisory platforms in Kano, Nigeria.

<br>

## Project Overview

This project is part of the Omdena Kano Nigeria Chapter challenge, aimed at leveraging AI to improve agricultural sustainability and efficiency in Kano, Nigeria.


The project focuses on data collection, preprocessing, exploratory data analysis (EDA), and Data Science & ML driven insights to support precision farming and resource optimisation.

<img width="450" alt="Screenshot 2025-03-31 at 1 15 10 PM" src="https://github.com/user-attachments/assets/6df28f3e-7bc0-42f2-9169-ebecd75aa263" />


<br>

### Objective

To collect, clean, analyse, and extract meaningful insights from climate and agricultural data to help local farmers make informed decisions, thereby improving crop yield and resource management.

Based on expert recommendations, the primary focus is on developing a **data-driven weather analysis system** due to its significant impact on farming operations. This is further discussed below:

### 1. Prioritising Weather Analysis Over Other Challenges

- Most impactful solution: Affects all aspects of farming, including planting, irrigation, and fertilizer application.
- Direct impact on crop survival: Unpredictable weather has led to a 25% increase in crop failures over five years.
- Foundation for other improvements: Weather prediction must come before resource management and storage optimization.


### 2. Feasibility

- Technical feasibility within an 8-12 week timeline:
Historical weather data is available for Kano State.
Machine learning models for weather prediction are well-established but suitability for the project will need to be further investigated.

- Cost-effective implementation:
Minimal physical infrastructure (delivered via mobile phones).
Lower maintenance costs than sensor-based solutions.
Can push updates remotely without requiring farmers to install new devices.

- Accessible for farmers:
Voice-based alerts in Hausa (suitable for non-literate users).
Simple, audio-based interface that integrates with traditional weather knowledge.
Requires minimal training for farmers.

<img width="800" alt="Screenshot 2025-03-28 at 10 26 47 PM" src="https://github.com/user-attachments/assets/51fb817e-acd3-4d9e-9554-7f47dc62ab25" />

<br>

### 3. Limitations of the Weather Prediction System

Not a full-scale weather forecasting system.

Focused on agricultural decision-making, such as:
- Rainy season start/end analysis and predictions
- Best planting windows based on historical trends seen in soil moisture, precipitation, temperature and wind speed.
  
Will not provide:
- Detailed daily forecasts.
- Exact rainfall amounts.
- Precision meteorological data (humidity, wind speeds, etc.).

<img width="800" alt="Screenshot 2025-03-28 at 10 27 12 PM" src="https://github.com/user-attachments/assets/0ff71269-2328-4bfe-9dfc-0d8e929ed120" />


### 4. Strategy for Maximising Usefulness

- Combining multiple data sources:
  
Historical weather data from NASA's POWER Database and NiMet (Nigerian Meteorological Agency).
Possible inclusion of satellite imagery for cloud and weather pattern analysis.
Traditional farming knowledge (if documented and available).

- Clear, actionable communication for farmers:
  
Instead of saying: “60% chance of precipitation”,
→ Say: “Strong signs of rain likely. Good time to prepare your fields this week.”

Use Hausa voice alerts to ensure accessibility.

- Implementation via mobile-based delivery system:
  
Voice alerts in Hausa.
Simple visual cues (e.g., sun/rain icons for illiterate users).
Basic SMS alerts as a backup for those without smartphones.

- Community engagement & trust-building:

Work with local agricultural extension officers.
Regular feedback from farmers to refine accuracy.
Transparency about the model’s limitations and reasoning behind predictions.


---

<br>

## Data Collection

<img width="500" alt="Screenshot 2025-03-26 at 3 18 26 PM" src="https://github.com/user-attachments/assets/b9ed9624-5266-4e86-9bff-8d6bbe5e9830" />


Data was sourced from NASA's POWER (***P***rediction ***O***f ***W***ordwide ***E***nergy ***R***esources) Database. Extensive DAILY agroclimatology data was collected for 37 LGAs (Local Government Areas) spanning 12 metrics (including soil moisture, rainfall, humidity, wind speed and temperature) for 11 years from 2014-2024, totalling around 1.8 million data points.

The 12 metrics are:
1. Temp-avg - The average air (dry bulb) temperature at 2 meters above the surface of the earth.
2. Temp-max - The maximum hourly air (dry bulb) temperature at 2 meters above the surface of the earth in the period of interest.
3. Temp-min - The minimum hourly air (dry bulb) temperature at 2 meters above the surface of the earth in the period of interest.
4. Relative humidity at 2 meters
5. Precipitation (mm/day)
6. Wind speed at 2 meters avg
7. Wind speed at 2 meters max
8. Wind speed at 2 meters min
9. Wind direction at 2 meters
10. Surface soil wetness - The amount of water and water vapor present in the soil. Top indicates the upper 5 cm of soil. Values range from 0 for completely dry conditions to 1 for completely saturated soil.
11. Root zone soil wetness - The amount of water and water vapor available to plants in the root zone, generally considered to be the upper 200 cm of soil, expressed as the proportion of water present in a given amount of soil. Values range from 0 for completely dry conditions to 1 for completely saturated soil.
12. Profile soil moisture - The amount of water and water vapor present in the soil. Profile indicates the layer from the surface down to the bedrock. Values range from 0 for completely dry conditions to 1 for completely saturated soil

<br>

## Data Processing and Analysis

Warawa South Kano Preprocessing and EDA - https://colab.research.google.com/drive/1RVelPBkLtTUZ28Kch5WPId4YN9mArF-Q?usp=sharing

Comprehensive Kano EDA - https://colab.research.google.com/drive/1m5z6qInxD9VIV2PmRFIQXJY5ynM4aIol?usp=sharing

<br>

1. Data Cleaning

Handling missing values, standardising formats and adding data on region, latitude, longitude etc.

<img width="400" alt="Screenshot 2025-03-26 at 6 03 37 PM" src="https://github.com/user-attachments/assets/a155bfb2-8b7c-444d-8ed0-431338eff186" />
 <img width="400" alt="Screenshot 2025-03-26 at 6 03 50 PM" src="https://github.com/user-attachments/assets/dae1c284-388b-4cf4-9dee-053110f601a9" />



2. Exploratory Data Analysis (EDA)

Understanding key weather patterns and trends.

Identifying correlations between factors like soil quality, rainfall, and crop yield.

Visualising variable patterns across 11 years and also averaging out for a single calendar year.

<img width="400" alt="Screenshot 2025-03-26 at 6 04 10 PM" src="https://github.com/user-attachments/assets/ca6dd83b-451a-4d12-9dc5-4d5272ed425e" />
 <img width="400" alt="Screenshot 2025-03-26 at 6 05 02 PM" src="https://github.com/user-attachments/assets/b9ba6beb-b0e7-4779-af86-24500ef3ca75" />
 <img width="400" alt="Screenshot 2025-03-26 at 6 05 14 PM" src="https://github.com/user-attachments/assets/8909bdac-76ec-4747-b272-784e5e2c6bee" />


<br>

## Modelling and Forecasting Focus: Crop Window Recommendations, Weather Analysis

Warawa South Kano Modelling and Historical Data Analysis - https://colab.research.google.com/drive/1gJ42fFLMw04eksFc23ot-6QiCr0eSmlK?usp=sharing

Time Series Modelling - https://colab.research.google.com/drive/1D1-mTUh3KbwY6d9xT6-5fMYro8Zua6Zb?usp=sharing 

<br>

Based on expert recommendations, the primary focus is on delivering farming insights and possibly a weather prediction system due to its significant impact on farming operations.

- Provide warnings on rainy season start/end based on historical data.

- Identify likely dry spells during the growing season based on historical data.

- Offer best planting windows based on historical rainfall patterns.

- Augment the above with a weather prediction system if found to be technically feasible.

<br>

Why historical analysis and forecasting of weather patterns?

- Direct impact on farming – Affects planting schedules, irrigation, and crop survival.

- 25% increase in crop failures over five years – Unpredictable weather is a leading cause.

- Seasonal nature of farming – Requires reliable weather insights.

- Foundation for future solutions – Supports resource management and storage optimisation.

<img width="700" alt="Screenshot 2025-03-29 at 11 01 28 PM" src="https://github.com/user-attachments/assets/f31b83ec-c97a-480a-adf2-d1ee1bda86cb" />




### Proposed Approach (Statistical Analysis of Historical Data, Time Series Modelling and Forecasting)

Analysing historical weather data using ML and Statistical Methods:
- Statistical analysis of historical data to determine desirable sowing windows (e.g. statistical models of soil moisture, moving average rainfall patterns). This has been done in accordance with the recommended Planting Readiness Framework to create interpretable and informative charts like the one above
- Build models for both predicition and classification tasks (possible approaches inclued - LSTM, Random Foresests, Time Series Forecasting, among others). However, doing this accurately can be challenging because of the complexity of weather forecasting.

For weather forecasting, my focus has been on using **time series analysis**. I used the **Exponentially Weighted Moving Average (EWMA) based Holt Winters model** to decompose weather time series into its **level, trend and seasonality components**. These components were combined using an **additive approach** to understand the movement patterns of temperature, soil moisture, precipitation and wind speed. Different forecasting horizons were tested and a **monthly rolling forecast methodology** was found to be a good balance of predictive accuracy and forecast horizon. It was found that the Holt Winters model performed reasonably well in forecasting temperature, soil moisture and temperature, but did not do as well on precipitation and wind speed due to their high volatility and unpredictability.

Some of the time series decompositions and forecast testing charts can be seen below:

<img width="1511" alt="temp" src="https://github.com/user-attachments/assets/bb7d4286-825a-4a93-8872-0ea9a75e9e8a" />

<img width="1511" alt="soil_mois" src="https://github.com/user-attachments/assets/21277f04-dc83-478a-b06f-4c3cc5374da0" />


<br>

<br>

<br>

**High-Priority Metrics (Direct Impact on Farming):**

These metrics are essential for understanding weather patterns, identifying drought risks, and determining best planting times:

1. Precipitation 🌧️
- Determines rainy season start and end, helping farmers time their planting.
- Helps identify drought periods affecting crop growth.
- Key for irrigation planning.

<img width="775" alt="Screenshot 2025-03-26 at 3 13 48 PM" src="https://github.com/user-attachments/assets/a974de9f-3907-44f4-ab24-d1157a9ac9ad" />

2. Temp-avg (Average Air Temperature) 🌡️
- Affects crop growth cycles and water needs.
- Helps predict heat stress on crops.
- Impacts evapotranspiration, crucial for water management.

3. Soil Moisture 💧
- Useful for early seed germination and detecting dry spells.
- Useful for determining optimal planting periods based on expected surface soil moisture and root zone soil moisture (that tracks surface wetness).
- Supports decision-making for irrigation adjustments.




