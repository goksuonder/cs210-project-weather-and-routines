## Project Overview

This project is about understanding how the weather affects my daily health and routines. I want to see how different weather conditions (like rain, temperature, and wind) impact my walking activity and sleep quality. By comparing weather with walking and weather with sleep, I aim to find patterns that show:

- How much I walk depending on the weather.
- How walking in different weather conditions affects my sleep.
- How weather affects my sleeping.
- How the combination of weather and walking affetcs my sleep routines.

---

## Dataset Description

- **Sleep Data:** My daily sleep duration, collected from the iPhone Health app. The data starts from **July 1st**.
- **Activity Data:** Step counts and calories burned, also from the iPhone Health app.
- **Weather Data:** Daily weather information, such as temperature, rain, and wind speed, retrieved using the **Open-Meteo API**.

---

## Project Idea

The main idea of this project is to discover the connection between weather, walking, and sleep. I want to answer questions like:

- Do I walk more on sunny days or rainy days?
- Does walking more (or less) on certain days affect how well I sleep that night?
- How does weather directly impact my sleep?

By exploring these questions, I hope to learn more about my personal habits and how I can improve my health based on the weather.

---

## Plan

1. **Data Collection**:

   - Export sleep and walking data from my iPhone Health app.
   - Use the Open-Meteo API to get weather data for the same days.
2. **Data Preprocessing**:

   - Clean the data and combine it by matching the dates.
3. **Analysis**:

   - Check trends in sleep, walking, and weather.
   - Compare weather conditions with walking activity and sleep quality.
4. **Visualization**:

   - Create simple graphs to show the relationships between weather, walking, and sleep.
5. **Insights**:

   - Write down what I learn from the analysis and suggest improvements for my daily routine.
6. **Machine Learning**

   -Research machine learning methods which fits best in my case.
---

## Motivation

I often wonder how the weather affects my health. For example, do I walk less when it rains? If I walk more, does that help me sleep better at night? Through this project, I hope to understand these connections and use this knowledge to improve my sleep and activity based on the weather.

---

## Data Source

1. **iPhone Health App**:
   - My sleep and walking data were exported directly from the app. However iphone provides a complicated xml file so it has cleaned by hand and converted to csv.

2. **Visual Crossing Weather Data**:

   - Historical weather data (temperature, rain, and wind) is free and easy to access.
   - **Links**: [Visual Crossing Link](https://www.visualcrossing.com/weather/weather-data-services#)
   - Latitude and longitude coordinates of Istanbul are: 41N 29E

---

## Limitations

1. **Limited Time Range**:
   - My sleep and activity data only start from **July 1st**.
2. **Data Accuracy**:
   - Sleep and walking data depend on the iPhone Health app, so there might be small errors.
3. **Daily Weather**:
   - Weather data is daily, so it does not include changes within a single day.

---

## Repository Structure

- `datas/`: Contains the sleep, activity, and weather datasets.
- `visuals/`: Includes all the graphs created during the analysis.
- `analyses/`: Includes all the analyses notebooks
- `README.md`
