# Analysis-of-Flight-Schedules
Airline Performance Overview

![Flight_analysis](https://github.com/AvishkarK07/Analysis-of-Flight-Schedules/blob/main/images/flights.jpg)

<H1>Tool Used :</H1>
<img width="315" height="250" alt="Screenshot 2025-09-14 211235" src="https://github.com/AvishkarK07/Power-Bi-Phone_Pay/blob/main/images/power%20bi.jpeg" />

## Overview

This dataset contains flight records including scheduling, airlines,
origins, destinations, delays, and aircraft details.\
It includes **15,000 rows** and **10 columns**.

## Columns

-   **FlightID**: Unique identifier for each flight.\
-   **Date**: Scheduled flight date.\
-   **Airline**: Airline operating the flight.\
-   **Origin**: Departure airport code.\
-   **Destination**: Arrival airport code.\
-   **DepartureTime**: Scheduled departure time.\
-   **ArrivalTime**: Scheduled arrival time.\
-   **Status**: Flight status (e.g., On Time, Cancelled).\
-   **DelayMinutes**: Delay in minutes.\
-   **AircraftType**: Type of aircraft used.

## File Information

-   Total records: 15,000\
-   File type: Excel (.xlsx)

  <h1>🛠️Data Cleaning Recommendations</h1>

    - Convert Date, DepartureTime, ArrivalTime to datetime format
    
    - Treat missing values in delays or times
    
    - Standardize airport codes

    - Create new columns like:
    
        - Flight Duration
        
        - Delay Category (Low / Medium / High)
        
        - IsDelayed (Yes/No)

## Usage

This dataset can be used for: - Flight delay analysis\
- Airline performance insights\
- Predictive modeling\
- Aircraft usage patterns\
- Airport route analytics

## Notes

-   Time fields are stored as text and may require conversion for
    time-series analysis.
-   Dataset includes both historical and future-dated flights for
    simulation purposes.

<H1>✈️Airline Performance Overview</H1>
<img width="900" height="450" alt="Screenshot 2025-09-14 211235" src="https://github.com/AvishkarK07/Analysis-of-Flight-Schedules/blob/main/images/dash1.png" />

<H1>✈️Flight Monitoring Dashboard</H1>
<img width="900" height="450" alt="Screenshot 2025-09-14 211235" src="https://github.com/AvishkarK07/Analysis-of-Flight-Schedules/blob/main/images/dash2.png" />


<h1>🏁 Conclusion</h1>

This dataset provides a comprehensive view of flight operations, including schedules, airline performance, delays, and cancellations. With its rich attributes, it is highly suitable for building analytical dashboards, performing deep aviation insights, and developing data-driven decisions. By using visualizations, KPIs, and trend analysis, users can understand operational efficiency, identify delay patterns, and optimize airline performance


