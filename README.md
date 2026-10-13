
<img width="1746" height="866" alt="65" src="https://github.com/user-attachments/assets/8c7345c1-2eb6-49ff-b0fc-ed8fbfd0ac1d" />



# Bike Rental Demand Forecast

This project aims to develop a machine learning model to predict bike rental demand in urban areas. By analyzing historical data. This information will be crucial for bike-sharing companies to optimize their operations, improve customer satisfaction, and achieve sustainable growth. The project will involve data exploration, feature engineering, model selection, and model evaluation using appropriate metrics. The final model will be deployed using streamlit for easy accessibility and real-time predictions.

## Project Structure
```
📂 BSRU
┣ 📜 Dataset File   
┣ 📜 Source Code File
┣ 📜 Streamlit Code File  
```

## Features
- Data Collection
- Data Preprocessing
- Exploratory Data Analysis
- Model Selection & Training
- Model Evaluation
- Predictions
- Model Deployment
- Results & Insights

## Technologies Used
- **Programming Language** - Python
- **Libraries & Frameworks** - Pandas, Numpy, Matplotlib, Seaborn, Scikitlearn
- **Storage** - CSV / Excel
- **Model Deployment** - Streamlit
- **Collaboration** - Jupyter Notebook

## Dataset
1. Source of the Dataset
- **Public Datasets** - Kaggle
2. Dataset Description
- **Number of rows and columns** - 16 Columns & 17380 Rows
3. Description of Important Features
- Date, Season, Year, Month, Hour, Holiday, Weekday, WorkingDay, Weather_Condition,
Tempature, aTempature, Humidity, WindSpeed, Casual, Registered, TotalCount

## Results & Visualizations
![image](https://github.com/user-attachments/assets/dec51a7f-1095-48bd-b22a-48de3f19eb70)
January (Low Sales)
- Cold Weather – If February had lower temperatures or harsher weather, people might have avoided biking.
- Seasonal Effects – If it falls in winter, fewer people might prefer outdoor travel.
- Shorter Days – Less daylight may reduce the willingness of people to rent bikes.
- Less Tourist Footfall – Tourism might be lower in February.

June (High Sales)
- Summer Season – Warm, pleasant weather makes biking a preferred mode of transport.
- Holidays & Events – June might have more holidays or public events increasing demand.
- Longer Days – More daylight hours allow people to ride bikes for longer periods.
- Peak Tourist Season – Tourists may rent bikes more frequently in June.

![image](https://github.com/user-attachments/assets/6c59613c-5abb-42ea-a436-d5bb8e4abd06)
High Graph at Certain Hours
- Morning Peak (Around 7-9 AM) – This is likely due to people commuting to work or school.
- Evening Peak (Around 5-7 PM) – Another surge occurs as people return home from work or school.
- Seasonal Differences – Summer, Fall, and Winter have higher peaks compared to Spring, possibly due to better weather conditions and more outdoor activities.

Low Graph at Certain Hours
- Late Night & Early Morning (12 AM - 5 AM) – Very few people rent bikes during these hours due to low demand and safety concerns.
- Midday Dip (10 AM - 3 PM) – Many people are at work or school, leading to reduced rentals.
- Spring Season Overall Lower – The blue line (Spring) is lower compared to other seasons, likely due to colder or rainy weather discouraging biking.

![image](https://github.com/user-attachments/assets/b5153274-4d1e-47df-b9da-2c42c3dffd12)
![image](https://github.com/user-attachments/assets/89c9a36f-420e-4bda-bd0f-92bfea141e1a)
Bike Rentals Lower on Holidays
- Less Commuting Demand – On regular days, many people rent bikes for commuting to work or school. On holidays, this demand drops.
- Office & Business Closures – Fewer people go to offices, reducing the usual weekday rental surge.
- Alternative Travel Options – People might prefer using personal vehicles, public transport, or walking instead of renting bikes on holidays.
- Weather & Seasonal Factors – Holidays in winter or extreme weather conditions may further reduce bike rentals.

Bike Rentals Higher on Non-Holidays
- Work & School Travel – Daily commuters rent bikes to go to work, school, or university.
- Consistent Travel Patterns – On non-holidays, people follow a fixed routine, ensuring steady demand.
- Rush Hour Peaks – As seen in the hourly distribution chart, non-holiday days have distinct morning and evening peaks, driving overall rentals higher.

![Yearly Avg Bike Rentals](https://github.com/user-attachments/assets/e96036db-3b2f-4c5b-9d26-e58318aa0d29)

Increase in Bike Rentals in 2011 vs 2012
- Improved Awareness & Adoption – The bike rental service might have gained more popularity in 2012 as more people became aware of it.
- Infrastructure Improvements – More rental stations or better biking infrastructure.
- Favorable Weather Patterns – Compare the weather conditions (temperature, humidity, wind speed) between 2011 and 2012 to see if 2012 had more favorable conditions.
- Policy Changes – Any changes in government regulations, promotions, or subsidies for bike rentals in 2012.
- Tourism & Events – More events or tourists in 2012 may have led to higher demand.

## Model Deployment

### Input Parameters

1. Season - (1–4) - Springer, Summer, Fall, Winter

2. Year - 2011, 2012

3. Month - (1-12) - 1 - January, 2 - February, 3 - March, 4 - April, 5 - May, 6 - June,
    7 - July, 8 - August, 9 - September, 10 - October, 11 - November, 12 - December

4. Hour - (0-23)

5. Holiday - (0,1) - 0 - No, 1 - Yes

6. Weekday - (1-6) - 1 - Monday, 2 - Tuesday, 3 - Wednesday, 4 - Thursday, 5 - Friday, 6 - Saturday, 7 - Sunday

7. WorkingDay

8. Weather_Condition

9. Tempature

10. aTempature

11. Humidity

12. WindSpeed

13. Casual

14. Registered

15. TotalCount

![SS - ELR - P - DPT 1](https://github.com/user-attachments/assets/5a5b86cd-4821-42c2-b8ca-2a4bdb2cac9c)

![image](https://github.com/user-attachments/assets/cc49fd32-2117-4eef-94b7-7cd3cd84fa20)

![image](https://github.com/user-attachments/assets/7fcbb9c5-ca62-4f97-b293-b9ccabbcf834)
