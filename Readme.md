# Olympics Data Analysis Web Application

## Overview

Olympics Data Analysis is an interactive data visualization and analytics web application built using Streamlit. The application provides insights into Olympic history through country-wise, athlete-wise, and overall Olympic performance analysis.

Users can explore medal tallies, participation trends, athlete demographics, country performance, and sports dominance through interactive visualizations and dashboards.

---

## Features

### Medal Tally Analysis

* Overall medal tally across all Olympic editions
* Country-wise medal performance
* Year-wise medal performance
* Combined country and year filtering

### Overall Olympics Analysis

* Total Olympic editions
* Number of host cities
* Participating nations
* Sports and events statistics
* Athlete participation trends
* Nations participation trends
* Events growth over time
* Most successful athletes

### Country-wise Analysis

* Medal tally progression over the years
* Sports dominance heatmap
* Top-performing athletes for a selected country

### Athlete-wise Analysis

* Age distribution of athletes
* Age distribution of medal winners
* Sport-specific age analysis
* Height vs Weight analysis
* Male vs Female participation trends

---

## Dataset

### athlete_events.csv

Contains athlete-related information:

* Name
* Sex
* Age
* Height
* Weight
* Team
* NOC
* Games
* Year
* Season
* City
* Sport
* Event
* Medal

### noc_regions.csv

Contains:

* NOC codes
* Country/Region mapping

---

## Data Preprocessing

The preprocessing pipeline performs:

1. Filtering only Summer Olympics data.
2. Merging athlete data with country-region information.
3. Removing duplicate records.
4. One-hot encoding medal categories (Gold, Silver, Bronze).

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Streamlit
* Plotly
* Matplotlib
* Seaborn

---

### app.py

Main Streamlit application responsible for user interface, navigation, and visualization rendering.

### helper.py

Contains all data analysis, aggregation, filtering, and visualization helper functions.

### preprocessor.py

Handles data cleaning, preprocessing, merging, and feature engineering.

---

## Visualizations

### Line Charts

* Participating nations over time
* Events over time
* Athletes over time
* Country medal tally progression

### Heatmaps

* Sports vs Olympic years
* Country sports performance

### Distribution Plots

* Athlete age distribution
* Gold medalist age distribution by sport

### Scatter Plot

* Height vs Weight analysis with medal and gender classification

---

## Key Insights Generated

* Evolution of Olympic participation across countries
* Growth of events and sports over time
* Dominant sports for different countries
* Most successful athletes in Olympic history
* Athlete demographic trends
* Gender participation trends across Olympic editions

---

## Future Improvements

* Advanced filtering options
* Interactive dashboard optimization

---

## Learning Outcomes

* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Interactive dashboard development using Streamlit
* Data visualization using Plotly and Seaborn
* Working with large real-world datasets
* Building end-to-end data analytics applications
