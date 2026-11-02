# Statistics on Civilian Firearms Dashboard

## Overview
The Statistics on Civilian Firearms Dashboard is an interactive R Shiny application designed to explore global patterns of civilian firearm ownership and their relationship with military presence across countries and regions.

The dashboard enables users to analyze firearm ownership metrics through dynamic visualizations, correlation analysis, and interactive data exploration tools. By combining geographic filtering with exploratory analytics, the application provides an intuitive way to investigate regional trends and compare firearm ownership patterns across the world.

🔗 **Live Dashboard:** (https://knyarkoh.shinyapps.io/firearms/)

---

## Business Problem

Understanding civilian firearm ownership at a global scale often requires navigating large datasets and static reports that make comparisons difficult. This project addresses that challenge by providing an interactive platform that allows users to:

- Explore firearm ownership patterns by region and country.
- Compare subregional differences within continents.
- Investigate potential relationships between firearm prevalence and military personnel levels.
- Support evidence-based discussions using an accessible analytical interface.

---

## Dashboard Features

### Geographic Filtering
Users can filter results by:

- Africa
- Asia
- Europe
- Latin America
- North America
- Oceania

Additional filtering is available for African subregions:

- Eastern Africa
- Western Africa
- Northern Africa
- Southern Africa
- Middle Africa

### Summary Analytics
Provides a high-level overview of firearm ownership metrics for selected regions and countries.

### Interactive Visualizations
Includes dynamic charts for:

- Regional comparisons
- Country-level firearm ownership analysis
- Interactive exploration of trends and distributions

### Correlation Analysis
Examines relationships between:

- Firearms per 100 population
- Active military personnel
- Military personnel per million population

### Interactive Data Table
Users can:

- Search records
- Sort variables
- Filter data
- Compare countries
- Explore underlying datasets

---

## Dashboard Components

| Tab | Description |
|------|-------------|
| Summary | Overview statistics and key insights |
| Bar Chart | Country and regional firearm ownership comparisons |
| Correlation | Relationship analysis between firearms and military indicators |
| Data Table | Detailed exploration of the source data |

---

## Dataset

The analysis uses publicly available country-level data on firearm ownership and military personnel indicators.

### Key Variables

- Country
- Region
- Subregion
- Estimated Civilian Firearms
- Firearms per 100 Population
- Active Military Personnel
- Military Personnel per Million Population

---

## Technologies Used

- R
- Shiny
- Tidyverse
- ggplot2
- Plotly
- DT
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Interactive Data Visualization

---

## Skills Demonstrated

This project showcases:

- Interactive Dashboard Development
- R Shiny Application Design
- Data Cleaning and Transformation
- Exploratory Data Analysis
- Statistical Investigation
- Correlation Analysis
- Data Visualization
- User-Centered Analytics Design
- Business Intelligence and Reporting

---

## Key Learning Outcomes

Through this project, I developed and demonstrated the ability to:

- Build end-to-end analytics applications using R Shiny.
- Transform raw datasets into interactive decision-support tools.
- Create responsive filtering and visualization components.
- Design intuitive user interfaces for data exploration.
- Communicate analytical insights through interactive storytelling.

---

## Future Enhancements

Planned improvements include:

- Geographic mapping with Leaflet
- Country-to-country comparison tools
- Downloadable reports
- Additional demographic and socioeconomic indicators
- Predictive analytics and modeling
- Historical trend analysis

---

## Repository Structure

```text
├── data/
├── www/
├── app.R
├── server.R
├── ui.R
├── README.md
```

---

## Author

### Ebenezer (Eb) Obeng-Nyarkoh

Data Analytics | Business Intelligence | Data Visualization | R Shiny Development | Machine Learning

- LinkedIn: [Add Link]
- Portfolio: [Add Link]
- GitHub: [Add Link]

---

## Repository Description

Interactive R Shiny dashboard for exploring global civilian firearm ownership patterns, military population metrics, regional comparisons, and correlation analysis through dynamic visualizations and user-driven exploration.
