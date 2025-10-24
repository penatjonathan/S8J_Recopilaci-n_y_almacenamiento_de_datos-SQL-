# 🚕 Sprint 8 Project — Chicago Taxi & Zuber EDA + Weather Hypothesis (Python & SQL)

---

## 🧠 Project Description — Chicago Taxi EDA & Hypothesis Testing  

In this project, I explore Chicago’s taxi trip data to understand business performance and customer demand patterns.  
I analyze data from **multiple taxi companies and neighborhoods**, focusing on the number of completed trips, destination distribution, and the impact of weather on trip duration.

I work with three main datasets exported from SQL queries:  

1. `project_sql_result_01.csv` — taxi companies and trip counts (Nov 15–16, 2017)  
2. `project_sql_result_04.csv` — average trips per neighborhood (Nov 2017)  
3. `project_sql_result_07.csv` — trips from **the Loop** to **O’Hare Airport**, including weather conditions and durations  

The analysis includes:  
- Identifying the **top-performing taxi companies** and **most popular drop-off neighborhoods**.  
- Visualizing trip distributions to detect market concentration and demand hubs.  
- Testing the hypothesis that **rainy Saturdays** change the **average trip duration** from the Loop to O’Hare.  

This project demonstrates my ability to integrate **SQL-based data extraction** with **Python exploratory data analysis** and **statistical testing**, translating raw data into actionable insights for transportation and urban planning.

---
## 🧠 Project Description — Zuber Ride-Sharing Analysis  

I am working as a data analyst for **Zuber**, a new ride-sharing company launching in **Chicago**.  
My main goal is to discover patterns in the available data to better understand passenger preferences and the impact of external factors — particularly weather — on ride demand and duration.

I analyze a **relational database** containing taxi and weather information from Chicago.  
The analysis focuses on identifying high-demand neighborhoods, company performance, and weather effects on trip patterns.  
Finally, I test a **statistical hypothesis** on whether trip durations from **the Loop** to **O’Hare International Airport** change on **rainy Saturdays**.

### 📚 Database Description  
The database includes four main tables:

**neighborhoods**  
- `neighborhood_id` — neighborhood code  
- `name` — neighborhood name  

**cabs**  
- `cab_id` — cab code  
- `vehicle_id` — technical vehicle ID  
- `company_name` — taxi company name  

**trips**  
- `trip_id` — trip identifier  
- `cab_id` — cab operating the trip  
- `start_ts` — trip start timestamp (rounded to hour)  
- `end_ts` — trip end timestamp (rounded to hour)  
- `duration_seconds` — trip duration in seconds  
- `distance_miles` — trip distance in miles  
- `pickup_location_id` — pickup neighborhood code  
- `dropoff_location_id` — dropoff neighborhood code  

**weather_records**  
- `record_id` — weather record code  
- `ts` — timestamp of the weather record (rounded to hour)  
- `temperature` — temperature at the time of recording  
- `description` — brief weather description (e.g., “light rain”, “scattered clouds”)
  
The project combines **SQL** (data extraction and joins) with **Python** (EDA, visualization, and hypothesis testing) to uncover insights that guide Zuber’s early market strategy.
---

