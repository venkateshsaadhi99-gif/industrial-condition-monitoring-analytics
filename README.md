# industrial-condition-monitoring-analytics
Industrial Condition Monitoring and Hydraulic System Performance Analytics using PostgreSQL and Power BI
# Industrial Condition Monitoring & Hydraulic System Analytics

## Project Overview

This project uses PostgreSQL and Microsoft Power BI to analyze industrial equipment sensor readings, fault records and hydraulic system performance.

The objective is to transform raw industrial data into interactive dashboards that help users understand equipment conditions, identify fault patterns and explore hydraulic system measurements.

## Tools & Technologies

- PostgreSQL
- Microsoft Power BI
- Power Query
- DAX
- SQL

## Project Dashboards

### 1. Equipment Overview & Fault Monitoring
- Equipment fault distribution
- Equipment-wise analysis
- Location-wise analysis
- Fault rate monitoring

### 2. Equipment Sensor Performance Analytics
- Average temperature
- Average pressure
- Average vibration
- Average humidity
- Equipment and location comparisons

### 3. Hydraulic System Performance & Condition Analytics
- Hydraulic cycle analysis
- Stable cycle measurements
- Pressure sensor comparison (PS1–PS6)
- Temperature sensor comparison (TS1–TS4)
- Hydraulic vibration distribution
- Motor power distribution
- Component condition analysis
- Cooling performance analysis

## Data Processing

1. Imported source datasets into PostgreSQL.
2. Explored tables and fields using SQL.
3. Connected PostgreSQL to Power BI.
4. Performed data-quality checks in Power Query.
5. Created analytical tables and measures.
6. Built interactive Power BI dashboards.

## Important Data Limitations

The equipment anomaly dataset does not contain a timestamp, so its measurements are analyzed as records rather than historical trends.

The hydraulic dataset contains cycle-level measurements. Its analysis focuses on cycle-level performance and condition distributions rather than time-series forecasting.

No predictive maintenance model or production deployment is claimed.

## Data Sources & Attribution

Document the original source, citation, license and redistribution permissions for each dataset here. The hydraulic dataset is from the UCI Machine Learning Repository.

## Author

Venkatesh

Power BI | SQL | PostgreSQL | Data Analytics
