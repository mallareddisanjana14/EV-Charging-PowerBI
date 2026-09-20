# EV-Charging-PowerBI
Interactive Power BI capstone project analyzing EV charging station performance, demand patterns, utilization, charger operations, waiting time, pricing, and geographic insights.

# EV Charging Network Operations & Demand Analytics

## Power BI Capstone Project

An interactive Power BI analytics project designed to analyze electric vehicle (EV) charging network operations, station performance, charging demand patterns, charger characteristics, waiting time, pricing, geographic activity, and operational efficiency.

This project transforms raw EV charging station data into an interactive business intelligence dashboard using Microsoft Power BI, Power Query, DAX, and data visualization techniques.

---

## 1. Project Overview

The rapid adoption of electric vehicles is increasing the demand for reliable and efficient EV charging infrastructure.

Charging network operators need to understand:

- Which stations experience higher utilization?
- When is charging activity highest?
- Which charger types are most frequently observed?
- How does station availability vary?
- Which stations experience longer waiting times?
- How do cities and states differ in charging activity?
- How do charger types differ in power output, utilization, and availability?
- How do weather and traffic conditions relate to charging activity?
- How can operational data support better capacity and station management?

This project addresses these questions by analyzing EV charging station operational data through an interactive Power BI dashboard.

The dashboard provides a multi-page analytical view of the charging network, allowing users to explore station performance, demand patterns, geographic differences, charger characteristics, and operational metrics.

---

## 2. Project Objective

The primary objective of this project is to transform raw EV charging station data into an interactive business intelligence solution that provides meaningful insights into charging network operations.

The project focuses on five major analytical areas:

1. Station Performance
2. Charging Demand and Time Patterns
3. Geographic Analysis
4. Charger and Operational Analysis
5. Business Insights and Decision Support

The final Power BI dashboard allows users to interact with the data using filters, slicers, charts, KPIs, maps, and analytical visuals.

---

## 3. Business Problem

EV charging network operators manage stations with different:

- Locations
- Charger types
- Power outputs
- Port capacities
- Availability levels
- Utilization rates
- Waiting times
- Pricing structures
- Network operators
- Environmental conditions
- Traffic conditions

Without proper analysis, it can be difficult to identify operational patterns and differences between stations.

For example, a station with high utilization may require closer monitoring of port availability, while a station with higher waiting time may indicate periods of increased demand relative to available charging capacity.

This project provides a data-driven way to analyze these operational patterns and present them through an interactive dashboard.

---

## 4. Key Questions Addressed

The dashboard is designed to answer questions such as:

### Station Performance

- Which stations have higher average utilization?
- Which stations have higher average waiting times?
- How does station status vary?
- How many charging ports are available at different stations?
- How does station performance differ across networks?

### Demand and Time

- Which hours have the highest charging activity?
- How does activity change throughout the day?
- How does charging activity vary by day of the week?
- How does activity differ between weekdays and weekends?
- How does activity vary by month?
- How does utilization change by hour?
- How does waiting time change throughout the day?

### Charger Analysis

- Which charger types have higher activity?
- How does utilization differ by charger type?
- How does power output differ by charger type?
- How does port availability differ by charger type?
- How does average charging price differ by charger type?
- How does average waiting time differ by charger type?

### Geographic Analysis

- Which cities have higher charging activity?
- How does charging activity vary by state?
- How does utilization differ between states?
- Which states have higher average waiting times?
- How are charging observations distributed geographically?

### External Factors

- How does charging activity vary under different weather conditions?
- Is charging activity associated with traffic congestion?
- How does temperature relate to charging activity?
- Does local event information provide additional context for demand patterns?

---

## 5. Tools and Technologies

### Microsoft Power BI

Used for:

- Interactive dashboard development
- Data visualization
- KPI creation
- Slicers and filters
- Geographic visualization
- Data exploration
- Business reporting

### Power Query

Used for:

- Data preparation
- Data type validation
- Data transformation
- Data cleaning
- Creating derived date information
- Preparing the dataset for analysis

### DAX

Used for:

- Analytical measures
- KPI calculations
- Average utilization
- Average waiting time
- Average session duration
- Average charging price
- Total observations

### CSV Dataset

The original EV charging station dataset is provided as a CSV file and acts as the primary source for the Power BI analysis.


---

## 6. Project Workflow

The project follows a standard Business Intelligence workflow:

```text
Raw EV Charging Data
        |
        v
Data Cleaning & Preparation
        |
        v
Data Modeling
        |
        v
DAX Measures & KPIs
        |
        v
Dashboard Development
        |
        v
Interactive Analysis
        |
        v
Business Insights
