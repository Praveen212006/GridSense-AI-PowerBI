# GridSense AI

## AI-Powered Smart Grid, Energy Demand & Anomaly Intelligence Platform

GridSense AI is a Power BI-based smart-grid analytics project developed to analyze energy consumption, solar generation, weather conditions, anomaly indicators, energy demand patterns, and risk-related information.

The project provides an interactive dashboard environment that converts smart-grid data into meaningful visual insights through KPI cards, charts, filters, and comparative analysis. It is designed to support the exploration of energy usage patterns across different regions, building types, meters, and time periods.

---

## Project Overview

Smart-grid systems generate large amounts of data from energy meters and related monitoring sources. Analyzing this data through raw tables can make it difficult to identify consumption patterns, unusual usage, risk indicators, and relationships between energy demand and environmental conditions.

GridSense AI addresses this reporting challenge by organizing smart-grid data into an interactive Power BI dashboard. The project combines energy consumption, solar generation, weather information, anomaly indicators, sensor health, risk-related values, and forecast-related fields into a structured analytical report.

The dashboard allows users to interact with the data using filters and visualizations, making it easier to examine different aspects of smart-grid performance.

---

## Objectives

The main objectives of GridSense AI are:

- Analyze smart-grid energy consumption patterns.
- Monitor solar energy generation.
- Identify anomaly and high-usage events.
- Analyze energy demand across different time periods.
- Examine energy consumption across regions and building types.
- Monitor sensor health and risk-related indicators.
- Analyze forecast-related energy values.
- Study weather and environmental conditions alongside energy consumption.
- Develop an interactive Power BI dashboard for smart-grid data analysis.
- Present complex energy data through clear KPIs and visualizations.

---

## Key Features

### Energy Consumption Analysis

The dashboard provides an overview of energy consumption and allows users to analyze consumption patterns across different regions, building types, meters, and time periods.

### Solar Generation Monitoring

Solar generation data is presented alongside energy consumption to provide a better understanding of renewable energy contribution within the dataset.

### Anomaly Analysis

The project provides visual analysis of anomaly events and high-usage events using the available anomaly-related fields in the dataset.

### Risk and Sensor Health Analysis

Risk categories, outage-risk indicators, and sensor-health information are presented through interactive visualizations to support exploratory analysis.

### Energy Forecasting Analysis

Forecast-related values are presented together with consumption information to support comparison and analysis of energy demand patterns.

### Weather Analysis

Temperature, wind speed, and humidity values are analyzed together with energy consumption and solar generation to provide environmental context.

### Interactive Dashboard

Users can explore the dashboard using filters such as:

- Date
- Region
- Building Type
- Meter ID

These filters allow users to analyze specific sections of the dataset without changing the underlying report structure.

---

## Dashboard Pages

The GridSense AI Power BI report contains four main dashboard pages.

### 1. Energy Overview

The Energy Overview page provides a summary of the major energy-related indicators in the dataset.

It includes:

- Total Energy Consumption
- Average Consumption
- Total Solar Generation
- Total Anomalies
- Energy Consumption Trends
- Consumption by Region
- Consumption by Building Type
- Solar Generation compared with Grid Consumption

This page provides the overall view of the dataset and helps users understand major energy consumption and generation patterns.

---

### 2. AI Energy & Anomaly Intelligence

The AI Energy & Anomaly Intelligence page focuses on unusual energy usage and grid-health-related indicators.

It includes:

- Total Anomalies
- High Usage Events
- Average Risk Score
- Healthy Sensors
- Anomaly Trends
- Risk Category Distribution
- High Usage and Anomaly Analysis
- Sensor Health
- Outage Risk Analysis

This page helps users explore unusual readings and understand the distribution of available anomaly, risk, and sensor-health indicators.

---

### 3. Energy Forecasting & Consumption Insights

The Energy Forecasting & Consumption Insights page focuses on energy demand and forecast-related analysis.

It includes:

- Forecasted Energy Demand
- Average Forecast Error
- Peak Consumption
- Total Meter Readings
- Actual vs Predicted Consumption
- Hourly Energy Demand Pattern
- Consumption by Day of Week
- Peak vs Off-Peak Consumption
- Building-Type-Based Consumption Analysis

This page helps users examine how energy demand varies across different periods and categories.

---

### 4. Weather & Environmental Intelligence

The Weather & Environmental Intelligence page focuses on the relationship between environmental conditions and energy-related information.

It includes:

- Average Temperature
- Average Wind Speed
- Average Humidity
- Total Solar Generation
- Temperature Trends
- Weather Impact on Energy Consumption
- Wind Speed vs Energy Demand
- Solar Generation by Temperature Range

This page provides environmental context for analyzing energy consumption and solar generation patterns.

---

## Dataset

The project uses a smart-grid dataset containing approximately 20,000 records.

The dataset contains information related to:

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

The dataset provides the required information for developing the four analytical dashboard pages.

---

## Dashboard Filters

The Power BI report provides interactive filtering capabilities for focused analysis.

### Date

Allows users to analyze energy-related information for a selected date or period.

### Region

Allows comparison of energy consumption and related indicators across different regions.

### Building Type

Allows users to examine energy usage patterns across different building categories.

### Meter ID

Allows analysis of individual meter-level information.

The combination of these filters enables users to explore the dataset at different levels of detail.

---

## Key Performance Indicators

The dashboard uses KPI cards to provide quick summaries of important metrics.

Important KPIs include:

- Total Energy Consumption
- Average Energy Consumption
- Total Solar Generation
- Total Anomalies
- High Usage Events
- Average Risk Score
- Healthy Sensors
- Forecasted Energy Demand
- Average Forecast Error
- Peak Consumption
- Total Meter Readings
- Average Temperature
- Average Wind Speed
- Average Humidity

The displayed KPI values change according to the selected filter context.

---

## Technologies Used

### Microsoft Power BI

Used to develop the interactive dashboards, visualizations, KPI cards, filters, and report pages.

### Power Query

Used for data cleaning, transformation, and preparation before creating the analytical report.

### DAX

Used to create calculated measures and KPI values for dashboard analysis.

### Python

Used as part of the project environment for data-related processing and analysis where applicable.

### CSV Dataset

Used as the primary structured data source for the smart-grid analysis.

---

## Project Structure

```text
GridSense-AI-PowerBI/
│
├── Dataset/
│   └── capstone_smartgrid_20000.csv
│
├── Documentation/
│   ├── GridSense_AI_Presentation(1).pptx
│   └── GridSense_AI_Project_Synopsis.pdf
│
├── PowerBI/
│   └── Grid Science AI.pbix
│
├── Python/
│    └── data cleaning.ipynp
│
├── Screenshots/
│   ├── Grid_Sense_Page 1.png
│   ├── Grid_Sense_Page 2.png
│   ├── Grid_Sense_Page 3.png
│   └── Grid_Sense_Page 4.png
│
└── README.md