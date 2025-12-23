# UPI Transaction Data Analysis Project

## Project Overview

This project demonstrates an end-to-end data analytics workflow using Power BI. The focus is on transforming raw transactional data into meaningful insights through proper data cleaning, structured data modeling, and interactive dashboard development.

## Project Objectives

* Clean and transform raw data for analysis
* Design a structured star schema data model
* Create KPIs and measures using DAX
* Build interactive Power BI dashboards for insights and decision-making

## Project Components

1. Raw Dataset

* Contains unprocessed transactional data
* Includes issues like:
  * Missing values
  * Inconsistent formats
  * Redundant columns

2. Data Cleaning & Transformation

* Performed using:
  * jupyter Notebook
    
* Key steps:
  * Removing duplicates
  * Handling null values
  * Data type corrections

## Data Modeling

1. Data Model Type: "Star Schema"

The project follows a Star Schema, which improves performance and simplifies analysis.

Tables Used

1. Fact Table
 
 Contains:
  * Transaction Amount
  * Transaction Count
  * Date Key
  * Customer Key
  * Other foreign keys

2. Dimension Tables

* Date Dimension – Time-based analysis (Year, Month, Quarter)
* Customer Dimension – Customer-related attributes
* Location Dimension – Location-based analysis (State, City, Region)

  Relationships

* One-to-Many relationships from dimension tables to the fact table
* Single-direction filtering for better performance

> 📷 *Data model diagram has been created in Power BI and included in the project files.*

## Measures and KPIs

 Key KPIs Designed

* Total Transactions
* Total Transaction Value
* Average Transaction Value
* Success Percentage
* Faliure Percentage

 DAX Usage

* Calculated Measures using:

  * SUM()
  * COUNT()
  * DIVIDE()


## Power BI Dashboard

The Power BI dashboard provides a clear and interactive view of the data. It is designed to help users easily analyze trends, compare performance, and understand key metrics.

### Dashboard Screenshots

The repository includes a Screenshots folder containing:
* Data model diagram view
* Final dashboard view with KPIs and visuals

##  Tools & Technologies

* jupyter Notebook
* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)

## Project Impact and Insights 
- Helped in understanding how raw data is converted into business-ready data
- Learned how proper data modeling improves report performance and clarity
- Gained hands-on experience in identifying meaningful KPIs
- Improved understanding of how dashboards support decisions making
- Strengthened practical Power BI and DAX skills

## Key Learnings
- Importance of structured data modeling
- Performance benefits of star schema design
- Practical usage of DAX for KPI creation
- Dashboard design 

## Author
Sumit Kumar  
Aspiring Data Analyst | Power BI |


