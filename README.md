# GridSense AI

## Author

**Developed by:** Praveen M  
**Organization:** Anudip Foundation  
**Batch:** AI&ML

## AI-Powered Smart Grid, Energy Demand & Anomaly Intelligence Platform

GridSense AI is a Power BI-based smart-grid analytics project developed to analyze energy consumption, solar generation, weather conditions, anomaly indicators, energy demand patterns, and risk-related information.

The project transforms smart-grid data into an interactive analytical dashboard using Microsoft Power BI, Power Query, and DAX. It provides users with a structured view of energy usage, anomaly indicators, forecasting-related values, and environmental conditions.

---

## Project Information

| Category | Details |
|---|---|
| Project Name | GridSense AI |
| Project Type | Data Analytics / Business Intelligence |
| Domain | Smart Grid and Energy Analytics |
| Primary Tool | Microsoft Power BI |
| Data Processing | Power Query |
| Analytical Language | DAX |
| Dataset | Smart Grid Dataset |
| Dataset Size | Approximately 20,000 records |
| Dashboard Pages | 4 |
| Developer | Praveen M |
| Organization | Anudip Foundation |
| Batch | AI&ML |

---

## Project Overview

Smart-grid systems generate large amounts of data from energy meters and related monitoring sources. Working directly with raw data can make it difficult to identify consumption patterns, unusual usage, risk indicators, and environmental relationships.

GridSense AI provides an interactive Power BI environment for exploring these aspects of smart-grid data.

The dashboard combines energy consumption, solar generation, weather information, anomaly indicators, sensor health, risk-related values, and forecast-related fields into a structured analytical report.

Users can interact with the report using filters such as date, region, building type, and meter ID.

---

## Objectives

- Analyze smart-grid energy consumption patterns.
- Monitor solar energy generation.
- Identify anomaly and high-usage events.
- Analyze energy demand across different time periods.
- Compare energy consumption across regions and building types.
- Examine sensor health and risk-related indicators.
- Analyze forecast-related energy values.
- Study weather and environmental conditions alongside energy consumption.
- Develop interactive Power BI dashboards.
- Present complex energy data through clear KPIs and visualizations.

---

## Key Features

### Energy Consumption Analysis

Analyze energy consumption across different regions, building types, meters, and time periods.

### Solar Generation Monitoring

Examine solar energy generation and compare it with overall grid consumption.

### Anomaly Analysis

Explore anomaly events and high-usage indicators available in the dataset.

### Risk and Sensor Health Analysis

Review risk categories, outage-risk indicators, and sensor-health information through interactive visualizations.

### Energy Forecasting Analysis

Analyze forecast-related energy values and compare consumption patterns across different time periods.

### Weather Analysis

Examine temperature, wind speed, humidity, solar generation, and energy consumption together.

### Interactive Filtering

The dashboard provides filters for:

- Date
- Region
- Building Type
- Meter ID

---

# Dashboard Preview

## 1. Energy Overview

Provides an overall view of energy consumption, solar generation, anomaly events, and consumption patterns.

![Energy Overview](Screenshots/Grid_Sense_Page%201.png)

---

## 2. AI Energy & Anomaly Intelligence

Focuses on anomaly events, high-usage events, sensor health, risk categories, and outage-risk indicators.

![AI Energy and Anomaly Intelligence](Screenshots/Grid_Sense_Page%202.png)

---

## 3. Energy Forecasting & Consumption Insights

Provides analysis of forecast-related values, energy demand patterns, peak consumption, and consumption by time period.

![Energy Forecasting and Consumption Insights](Screenshots/Grid_Sense_Page%203.png)

---

## 4. Weather & Environmental Intelligence

Analyzes temperature, wind speed, humidity, solar generation, and energy consumption.

![Weather and Environmental Intelligence](Screenshots/Grid_Sense_Page%204.png)

---

## Dataset

The project uses a smart-grid dataset containing approximately 20,000 records.

The dataset includes information related to:

- Timestamp
- Date
- Month
- Day
- Meter ID
- Region
- Building Type
- Energy Consumption
- Next-Hour Consumption
- Historical Consumption Values
- Solar Generation
- Installed Solar Capacity
- Temperature
- Wind Speed
- Humidity
- Anomaly Indicators
- High Usage Indicators
- Sensor Health
- Outage Risk
- Risk Category
- Peak Period
- Forecast Error
- Forecast Error Band
- Temperature Range

---

## Dashboard Pages

### Energy Overview

The Energy Overview page provides:

- Total Energy Consumption
- Average Consumption
- Total Solar Generation
- Total Anomalies
- Energy Consumption Trends
- Consumption by Region
- Consumption by Building Type
- Solar Generation vs Grid Consumption

### AI Energy & Anomaly Intelligence

This page provides:

- Total Anomalies
- High Usage Events
- Average Risk Score
- Healthy Sensors
- Anomaly Trends
- Risk Category Distribution
- High Usage and Anomaly Analysis
- Sensor Health
- Outage Risk Analysis

### Energy Forecasting & Consumption Insights

This page provides:

- Forecasted Energy Demand
- Average Forecast Error
- Peak Consumption
- Total Meter Readings
- Actual vs Predicted Consumption
- Hourly Energy Demand Pattern
- Consumption by Day of Week
- Peak vs Off-Peak Consumption
- Building-Type-Based Consumption Analysis

### Weather & Environmental Intelligence

This page provides:

- Average Temperature
- Average Wind Speed
- Average Humidity
- Total Solar Generation
- Temperature Trends
- Weather Impact on Energy Consumption
- Wind Speed vs Energy Demand
- Solar Generation by Temperature Range

---

## Technologies Used

### Microsoft Power BI

Used for dashboard development, data visualization, KPI cards, filters, and report design.

### Power Query

Used for data cleaning, transformation, and preparation.

### DAX

Used for calculated measures and KPI analysis.

### Python

Used for data-related processing and analysis where applicable.

### CSV

Used as the primary structured data source.

---

## Project Structure

```text
GridSense-AI-PowerBI/
│
├── Dataset/
│   └── capstone_smartgrid_20000.csv
│
├── Documentation/
│   ├── GridSense_AI_Presentation.pptx
│   └── GridSense_AI_Project_Synopsis.pdf
│
├── PowerBI/
│   └── Grid Sense AI.pbix
│
├── Python/
│   └── data cleaning.ipynb
│
├── Screenshots/
│   ├── Grid_Sense_Page 1.png
│   ├── Grid_Sense_Page 2.png
│   ├── Grid_Sense_Page 3.png
│   └── Grid_Sense_Page 4.png
│
└── README.md