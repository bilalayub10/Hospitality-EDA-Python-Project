# Exploratory Data Analysis (EDA) in Hospitality Domain

## Table of Contents

- [Project Overview](#project-overview)  
- [Problem Statement](#problem-statement)  
- [Business Understanding](#business-understanding)  
- [Data Sources](#data-sources)  
- [Methodology](#methodology)  
- [Key Insights](#key-insights)  
- [Recommendations](#recommendations)  
- [Tools and Technologies](#tools-and-technologies)  
- [Let's Connect](#lets-connect)

## Project Overview

This project demonstrates an end-to-end **Exploratory Data Analysis (EDA)** workflow in the **hospitality domain** using **Python**.

As a data analyst, I analyzed **booking and revenue data** for **AtliQ Grands**, a leading hotel chain in India, to identify:

- Revenue leakage  
- Occupancy trends  
- Strategic opportunities  

The analysis uncovers **actionable insights** to help reverse declining **market share** and **revenue**, showcasing my ability to translate **raw data into business recommendations**.

The project leverages Python's **data manipulation** and **visualization libraries** to:

- Explore datasets  
- Clean inconsistencies  
- Derive metrics  
- Generate visualizations

View the full analysis in the Jupyter Notebook: Exploratory Data Analysis in the Hospitality Domain using Python.ipynb.

## Problem Statement

**AtliQ Grands**, a 20+ year-old hotel chain operating in **Delhi**, **Mumbai**, **Bangalore**, and **Hyderabad**, has experienced a decline in **market share** and **revenue** due to competitive pressures. The goal was to perform a **data-driven analysis** to pinpoint problem areas such as underperforming channels and occupancy gaps, and to provide **strategic recommendations** for recovery, including optimizing booking platforms and enhancing direct sales.

## Business Understanding

**Hotel Portfolio:** 7 brands (AtliQ Bay, AtliQ Blu, AtliQ City, AtliQ Grands, AtliQ Seasons, AtliQ Exotica, AtliQ Palace) across Luxury and Business segments.  
**Room Types:** Standard, Elite, Premium, Presidential.  
**Booking Channels:** AtliQ's website and third-party platforms (e.g., MakeMyTrip, LogTrip).  
**Key Metrics:** Revenue generated/realized, occupancy rates, booking platforms, and guest ratings.

Understanding these elements allowed me to align the analysis with business priorities, focusing on revenue optimization and competitive recovery.

## Data Sources

The analysis uses five datasets (dimension and fact tables) covering May-July 2022:

- **dim_date.csv**: Calendar details (dates, week numbers, day types).  
- **dim_hotels.csv**: Hotel properties (name, category, city).  
- **dim_rooms.csv**: Room types and classes.  
- **fact_aggregated_bookings.csv**: Aggregated bookings (capacity, successful bookings).  
- **fact_bookings.csv**: Detailed transactions (booking ID, dates, guests, revenue).

## Methodology

To solve the problem, I followed a structured data analytics workflow in Python:

1. **Data Exploration** – Understood the structure, quality, and distribution of the data.  
2. **Data Cleaning** – Handled missing values, corrected inconsistencies, and prepared data for analysis.  
3. **Data Transformation** – Merged datasets, created calculated fields, and reformatted data for insights generation.  
4. **Insights Generation** – Analyzed the transformed data to identify trends, patterns, and actionable recommendations.

## Key Insights

- **Occupancy Leaders:** Presidential rooms topped with 59.28% average occupancy; Delhi led cities at 61.51%.  
- **Weekend Spike:** Occupancy jumps from 50.88% (weekdays) to 72.34% (weekends), showing strong leisure demand.  
- **Revenue Hotspots:** Mumbai leads at ₹668.57M, followed by Bangalore (₹420.38M) and Hyderabad (₹325.18M).  
- **Platform Trends:** “Others” booking category drives ₹480.70M revenue, outpacing Makeyourtrip (₹233.13M) and Logtrip (₹129.04M).  
- **Ratings Gap:** Delhi customers rate highest (3.78/5), while Bangalore scores lowest (3.40/5).

## Recommendations

- **Capture Leisure Market:** Promote weekend packages and leisure experiences, especially in low-performing cities.  
- **Lift Weekday Occupancy:** Offer corporate tie-ups and business traveler discounts to close the weekday gap.  
- **Upsell Premium Rooms:** Highlight Presidential and Premium categories in marketing for higher margins.  
- **Channel Optimization:** Invest in high-performing platforms while incentivizing direct online bookings to cut commissions.  
- **Target Service Improvements:** Address rating gaps in Bangalore through service training and guest experience upgrades.

## Tools and Technologies

- **Python:** Core scripting 
- **Libraries:**  
  - Pandas: Data manipulation and exploration  
  - Matplotlib: Visualizations 
- **Environment:** Jupyter Notebook for interactive analysis

## Let's Connect

I’m passionate about leveraging data to solve business challenges in hospitality and beyond. Feel free to reach out for feedback, collaborations, or to connect:

*   **Email**: bilalayub.connect@gmail.com
*   **LinkedIn**: [https://www.linkedin.com/in/muhammad-bilal-ayub/](https://www.linkedin.com/in/muhammad-bilal-ayub/)







