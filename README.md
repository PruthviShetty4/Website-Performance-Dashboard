# Website-Performance-Dashboard

## Overview

This repository contains a Power BI dashboard created to visualize website performance metrics. The dashboard helps in understanding key performance indicators (KPIs) such as visitor conversion, bounce rate, session duration, and traffic sources. It allows stakeholders to make data-driven decisions to optimize the user experience and improve website performance.

## Dataset

The dataset used for this project is [`website_performance_analytics.csv`](website_performance_analytics.csv), which includes the following key variables:

- **Visitor_ID**: Unique identifier for each visitor.
- **Page_Views**: Number of pages viewed by the visitor during a session.
- **Session_Duration**: Duration of the session in seconds.
- **Bounce_Rate**: Percentage of visitors who leave the site after viewing only one page.
- **Conversion_Rate**: Percentage of visitors who complete a desired action (e.g., purchase, sign-up).
- **Traffic_Source**: Source from which the visitor arrived at the website (e.g., Direct, Organic Search, Paid Search).
- **Exit_Pages**: Pages from which visitors exit the site.
- **Load_Time**: Time taken to load the webpage.
- **Visitor_Type**: Type of visitor (e.g., New, Returning).
- **Location**: Geographic location of the visitor.

## Features of the Dashboard

- **KPI Cards**: 
  - Page Views
  - Session Duration
  - Bounce Rate
  - Conversion Rate
  
- **Visualizations**:
  - Donut charts for Bounce Rate and Conversion Rate by Visitor Type.
  - Bar chart showing average Conversion Rate by Traffic Source.
  - Map chart for Conversion Rate by Location.
  - Table showing top 100 visitors by average Conversion Rate.

## How to Use

1. Download the .pbix file and open it in Power BI Desktop.
You can interact with the dashboard by selecting different filters and analyzing various KPIs.
Interactivity:

2. Use the Exit_Pages filter at the top to explore the data based on exit pages.
The dashboard allows for in-depth analysis based on different visitor types, traffic sources, and geographic locations.
