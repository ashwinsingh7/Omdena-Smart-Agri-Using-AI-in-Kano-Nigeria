# Omdena Smart Agriculture Using AI in Kano, Nigeria

Omdena is a collaborative AI platform where data science and machine learning professionals can volunteer to work on projects in collaboration with startups, SMEs, NGOs and governments. Projects are focused on delivering data-driven technological solutions that drive positive social, environmental and economic impact.

Project Link: https://www.omdena.com/chapter-challenges/smart-farming-using-ai-for-sustainable-agriculture-in-kano-state-nigeria 

Project Repo: https://github.com/OmdenaAI/KanoNigeriaChapter_SmartFarming

<br>

## Project Overview

This project is part of the Omdena Kano Nigeria Chapter challenge, aimed at leveraging AI to improve agricultural sustainability and efficiency in Kano, Nigeria.


The project focuses on data collection, preprocessing, exploratory data analysis (EDA), and Data Science & ML driven insights to support precision farming and resource optimisation.

<img width="300" alt="Screenshot 2025-03-21 at 11 27 48 PM" src="https://github.com/user-attachments/assets/ff64f20c-db9f-45dc-8c9a-6964da5ecbbe" /> 

<br>

### Objective

To collect, clean, analyse, and extract meaningful insights from climate and agricultural data to help local farmers make informed decisions, thereby improving crop yield and resource management.

Based on expert recommendations, the primary focus is on developing an **AI-powered weather prediction system** due to its significant impact on farming operations. This is further discussed below:

### 1. Prioritising Weather Prediction Over Other Challenges

- Most impactful solution: Affects all aspects of farming, including planting, irrigation, and fertilizer application.
- Direct impact on crop survival: Unpredictable weather has led to a 25% increase in crop failures over five years.
- Foundation for other improvements: Weather prediction must come before resource management and storage optimization.


### 2. Feasibility of the Weather Prediction System

- Technical feasibility within an 8-12 week timeline:
Readily available historical weather data for Kano State.
Machine learning models for weather prediction are well-established but suitability for the project will need to be further investigated.

- Cost-effective implementation:
Minimal physical infrastructure (delivered via mobile phones).
Lower maintenance costs than sensor-based solutions.
Can push updates remotely without requiring farmers to install new devices.

- Accessible for farmers:
Voice-based alerts in Hausa (suitable for non-literate users).
Simple, audio-based interface that integrates with traditional weather knowledge.
Requires minimal training for farmers.


### 3. Limitations of the Weather Prediction System

Not a full-scale weather forecasting system.

Focused on agricultural decision-making, such as:
- Rainy season start/end analysis and predictions
- Best planting windows based on historical trends seen in soil moisture, precipitation, temperature and wind speed.
  
Will not provide:
- Detailed daily forecasts.
- Exact rainfall amounts.
- Precision meteorological data (humidity, wind speeds, etc.).


### 4. Strategy for Maximising Usefulness

- Combining multiple data sources:
  
Historical weather data from NASA's POWER (**P**rediction **O**f **W**ordwide **E**nergy **R**esources) Database and NiMet (Nigerian Meteorological Agency).
Possible inclusion of satellite imagery for cloud and weather pattern analysis.
Traditional farming knowledge (if documented and available).

- Clear, actionable communication for farmers:
  
Instead of saying: “60% chance of precipitation”,
→ Say: “Strong signs of rain coming. Good time to prepare your fields this week.”

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


Data was sourced from NASA's POWER (**P**rediction **O**f **W**ordwide **E**nergy **R**esources) Database. Extensive DAILY agroclimatology data was collected for 37 LGAs (Local Government Areas) spanning 12 metrics (including soil moisture, rainfall, humidity, wind speed and temperature) for 11 years from 2014-2024, totalling around 1.8 million data points.

The 12 metrics are:
1. Temp-avg - The average air (dry bulb) temperature at 2 meters above the surface of the earth.
2. Temp-max - The maximum hourly air (dry bulb) temperature at 2 meters above the surface of the earth in the period of interest.
3. Temp-min - The minimum hourly air (dry bulb) temperature at 2 meters above the surface of the earth in the period of interest.
4. Relative humidity at 2 meters
5. Precipitation
6. Wind speed at 2 meters avg
7. Wind speed at 2 meters max
8. Wind speed at 2 meters min
9. Wind direction at 2 meters
10. Surface soil wetness - The amount of water and water vapor present in the soil. Top indicates the upper 5 cm of soil. Values range from 0 for completely dry conditions to 1 for completely saturated soil.
11. Root zone soil wetness - The amount of water and water vapor available to plants in the root zone, generally considered to be the upper 200 cm of soil, expressed as the proportion of water present in a given amount of soil. Values range from 0 for completely dry conditions to 1 for completely saturated soil.
12. Profile soil moisture - The amount of water and water vapor present in the soil. Profile indicates the layer from the surface down to the bedrock. Values range from 0 for completely dry conditions to 1 for completely saturated soil

<br>

## Data Processing and Analysis


1. Data Cleaning

Handling missing values, standardising formats and adding data on region, latitude, longitude etc.


2. Exploratory Data Analysis (EDA)

Understanding key agricultural patterns and trends.

Identifying correlations between factors like soil quality, rainfall, and crop yield.

Visualising variable patterns across 11 years and also averaging out for a single calendar year

<br>

## Modelling and Forecasting Focus: Crop Window Recommendations, Weather Analysis

Based on expert recommendations, the primary focus is on delivering farming insights and possibly a weather prediction system due to its significant impact on farming operations.

- Provide warnings on rainy season start/end based on historical data.

- Identify likely dry spells during the growing season based on historical data.

- Offer best planting windows based on historical rainfall patterns.

- Augment the above with a weather prediction system if found to be technically feasible.


Why historical analysis and forecasting of weather pattenrs?

Direct impact on farming – Affects planting schedules, irrigation, and crop survival.

25% increase in crop failures over five years – Unpredictable weather is a leading cause.

Seasonal nature of farming – Requires reliable weather insights.

Foundation for future solutions – Supports resource management and storage optimisation.

<img width="700" alt="Screenshot 2025-03-26 at 3 03 06 PM" src="https://github.com/user-attachments/assets/bdf1b147-b3fa-4e1c-8eb8-c5feae929ab0" />



### Proposed Approach

Analysing historical weather data using ML and Statistical Methods:
- Statistical analysis of historical data to determine desirable sowing windows
- Potentially build models for both predicition and classification tasks
- Possible approaches inclued - LSTM, Random Foresests, Time Series Forecasting, among others

  <br>

**High-Priority Metrics (Direct Impact on Farming):**

These metrics are essential for predicting weather patterns, identifying drought risks, and determining best planting times:

1. Precipitation 🌧️
- Determines rainy season start and end, helping farmers time their planting.
- Helps identify drought periods affecting crop growth.
- Key for irrigation planning.

<img width="775" alt="Screenshot 2025-03-26 at 3 13 48 PM" src="https://github.com/user-attachments/assets/a974de9f-3907-44f4-ab24-d1157a9ac9ad" />


2. Temp-avg (Average Air Temperature) 🌡️
- Affects crop growth cycles and water needs.
- Helps predict heat stress on crops.
- Impacts evapotranspiration, crucial for water management.
  
3. Root Zone Soil Wetness 🌱
- Indicates water availability for plants, drought conditions, and soil moisture retention.
- Helps determine when to irrigate and how much water is needed.
- More relevant than surface soil wetness since roots absorb water deeper in the soil.

4. Surface Soil Wetness 💧
- Useful for early seed germination and detecting dry spells.
- Helps prevent waterlogging issues in low-lying farms.
- Supports decision-making for irrigation adjustments.

The ML model development and testing stage may be followed by voice-activated mobile interface in Hausa for accessibility (if feasible within the project timeline).




