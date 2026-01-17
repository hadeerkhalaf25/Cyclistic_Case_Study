# Cyclistic_Case_Study 🚲

## Business Task
Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.


The main business question is:
1. How do annual members and casual riders use Cyclistic bikes differently? 
2. Why would casual riders buy Cyclistic annual memberships?  
3. How can Cyclistic use digital media to influence casual riders to become members?

---

## Data Source
The analysis uses **Cyclistic historical bike trip data** made publicly available by Motivate International Inc.  
The data includes ride information such as:
- Ride type
- Ride start and end times
- Day of week
- Ride duration
- User type (casual vs member)

📌 Note: Data has been processed and analyzed in accordance with the data’s license and privacy guidelines.

---

## Tools Used
- **R**
- tidyverse (dplyr, ggplot2, lubridate)
- R Markdown

---

## Data Cleaning & Preparation
The following steps were performed:
- Removed missing and invalid values
- Calculated ride length
- Extracted day of week and month
- Standardized column names
- Filtered out rides with negative or zero duration

---

## Key Insights
- **Casual riders** tend to:
  - Ride more on **weekends**
  - Have **longer average ride durations**
  - Show higher activity during **summer months**

- **Annual members** tend to:
  - Ride more frequently on **weekdays**
  - Have **shorter but more consistent rides**
  - Use the service more regularly throughout the year

These patterns suggest that casual riders use Cyclistic mainly for **leisure**, while members use it more for **daily transportation**.

---

## Recommendations
Based on the analysis, Cyclistic could:
1. Introduce **weekend-focused membership promotions** for casual riders.
2. Launch **seasonal marketing campaigns** during peak summer months.
3. Offer **trial memberships or discounts** for users with long ride durations.
4. Promote membership benefits related to **daily commuting convenience**.

---

## Files in This Repository
- `Bike Share.Rmd` → Full R Markdown analysis
- `Bike-Share.html` → Rendered report
- `scripts/` → R scripts for cleaning and analysis
- `images/` → Visualizations used in the report

---

## Author
**Hadeer Khalaf**  
Aspiring Data Analyst | Workforce Supervisor  
Skills: R, Data Cleaning, Data Visualization

---

## Acknowledgments
This project is part of the **Google Data Analytics Professional Certificate** Capstone.
