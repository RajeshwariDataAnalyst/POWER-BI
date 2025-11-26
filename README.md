#  Public Transport Delays with Weather & Events 
 ##  1. Projects Overview and Objective:
 The projects involves Cleaning, transforming and analysing public transport,weather and event data using **EXCEL**,
 And creating an intractive **Power BI** reports to uncover how external factor influence transport delays.
 
 The main objective is to apply data pre- processing techniques in Excel and build an interactive POwer bi 
 report to analyse how weather condition local events impact in public transport delays, enabling more informed decision-making.

 ## 2. Data Sources:
**Source Description and Timeline:**    KAGGLE and 2024-2025.

**Domain** Transportation Analytics

## 3. Problem Statement:
- To analyze delay patterns across different transport types, routes, and time periods to identify the major sources of travel disruption.

- To study how weather conditions such as rain, fog, snow, and storms affect departure and arrival delays.

- To evaluate the impact of events, traffic congestion, and peak hours on public transport performance.

- To understand overall passenger flow and external factors to improve prediction models and enhance transport planning.

## 4. Attribute (Column /Features) Details: 
| Attribute Name | Data Type | Description |
|---------------|------------|-------------|
| Trip_ID | String / Categorical | Unique identifier for each trip | 
| Date | Date | Date on which the trip occurred |
| Time | Time | Scheduled start time of the trip |
| Transport_Type | Categorical | Type of transport (Bus, Train, Tram, Metro) |
| Route_No | Categorical | Route number assigned to the trip |
| Origin_Station | Categorical | Starting station of the trip |  
| Destination_Station | Categorical | Ending station of the trip |
| Scheduled_Departure | Time | Planned departure time |
| Actual_Departure | Time | Actual departure time recorded |
| Departure_Delay_Min | Numeric (Integer) | Delay in minutes for departure |
| Scheduled_Arrival | Time | Planned arrival time |
| Actual_Arrival | Time | Actual arrival time recorded |
| Arrival_Delay_Min | Numeric (Integer) | Delay in minutes for arrival |
| Weather_Condition | Categorical | Weather during the trip (Rain, Fog, Storm, Clear, etc.) |
| Temperature_C | Numeric (Float) | Temperature in Celsius |
| Humidity_% | Numeric (Integer) | Humidity percentage
| Wind_Speed_Kmh | Numeric (Integer) | Wind speed in km/h |
| Precipitation_mm | Numeric (Float) | Rainfall or precipitation level |
| Event_Type | Categorical | Type of public event (Concert, Festival, Sports, Protest, None) |
| Event_Attendance_Est | Numeric (Integer) | Estimated number of attendance |
| Traffic_Congestion_Index | Numeric (Integer) | Congestion level on the route |
| Holiday | Categorical | Indicates if the day is a holiday or not |
| Peak_Hour | Categorical | Whether the trip occurred during peak or off-peak hours |
| Weekday | Categorical | Name of the day (Monday–Sunday) | 
| Day_Type | Categorical | Indicates whether it is a weekday or weekend |
| Season | Categorical | Season during the trip (Winter, Summer, etc.) |
| Delayed | Categorical (Yes/No) | Final label indicating if the trip was delayed |

## 5.Tools & Technologies:
•	 **Excel**: Data cleaning, transformation, and Pivot Tables.

• 	**Power BI**:  Data modelling, DAX calculations, Measure, Measure Table, visualization, and interactive dashboard creation.

## 6. Data Pre-processing (Excel/Power Query):
### Task Performed:
 -  **Data Cleaning & Transformation:** Removed duplicates, handled missing values, standardized formats, and created calculated fields.
 -   **Filtering & Sorting:** : Organized data to focus on relevant records.

## 6. Data Modelling & DAX (Power BI):
- **Data Model:** Established relationships between tables, defined cardinality, and created lookup tables where necessary.
![Alt text]([image-path "Optional title"](https://github.com/RajeshwariDataAnalyst/POWER-BI/blob/main/Data%20Model.png?raw=true))


   



         
