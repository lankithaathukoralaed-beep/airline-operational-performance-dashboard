# Airline Operational Performance and Passenger Satisfaction Dashboard

An interactive Tableau dashboard that examines how airline operational
performance influences passenger satisfaction. It combines flight
operations data, airline information and customer survey data.

## Objective
To find out whether airlines with more delays and cancellations receive
lower satisfaction scores, and to show where airlines should focus to
improve operations and customer experience.

## Data Sources
- flights.csv: flight dates, origin, destination, distance, delay minutes, cancellations
- airlines.csv: airline name, code, country, alliance, founded year
- satisfaction_survey.csv: satisfaction scores by feedback category and passenger class

## Visualizations
1. **Average Delay by Airline**: compares departure delays across airlines
2. **Cancellation Rate**: compares operational reliability of each airline
3. **Airline Reliability Scatter**: delay vs cancellation rate, coloured by satisfaction and sized by flight volume, split into four quadrants
4. **Distance vs Delay**: checks whether longer flights are linked to more delays (with trend line)
5. **Operational Performance by Origin City (Map)**: flight volume, average delay, satisfaction and cancellations by origin city
6. **Customer Satisfaction by Feedback Category**: shows the lowest-rated service areas by passenger class

## Key Insight
Operational performance has a direct influence on passenger experience.
Airlines with higher delays and cancellation rates are more likely to
have lower customer satisfaction. Reducing delays, improving reliability
and fixing the lowest-rated service categories can improve customer
loyalty and service quality.

## Tools Used
Tableau (data blending, calculated fields, reference lines, trend lines, map visualization)

## How to Open
Download `Airline_Operational_Performance_Dasboard_.twbx` and open it in
Tableau Desktop or Tableau Public (both are free to try).

## Preview
![Dashboard Screenshot](dashboard.png)
