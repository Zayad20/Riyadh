# Riyadh Real Estate Rental Market Analysis

DashBoard link : 
https://app.powerbi.com/view?r=eyJrIjoiODBlNjlhNDgtOWU0OS00MzZmLWJlZjAtZTI4OGZjYmE5MTVjIiwidCI6IjZmMGJiNzJmLTUzNzctNGRkZi05MzZhLWI2YzcyYmYyMWFlMiIsImMiOjF9&pageName=33164b0330a2f24c169d

## 📖 Project Overview

This project provides a comprehensive analysis of the real estate rental market in Riyadh, Saudi Arabia. The primary objective is to extract actionable insights from publicly available listings to help potential renters, investors, and market analysts understand pricing trends, neighborhood variations, and the key factors influencing rental costs.

The entire workflow, from data acquisition to visualization, was automated to create a dynamic and interactive dashboard that serves as a single source of truth for market intelligence.

## ⚙️ Methodology & Tech Stack

The project was executed in three main phases:

1.  **Data Acquisition:**

      * **Tool:** `Python` with the `Selenium` library.
      * **Process:** A web scraper was developed to automatically navigate the "Aqar" real estate platform, systematically collecting data from thousands of rental listings across Riyadh's districts.

2.  **Data Cleaning and Transformation (ETL):**

      * **Tool:** `Python` with the `Pandas` library.
      * **Process:** The raw, unstructured data was rigorously cleaned. This involved handling missing values, standardizing text, converting data types, and removing duplicate entries to ensure data integrity.

3.  **Data Visualization and Analysis:**

      * **Tool:** `Microsoft Power BI`.
      * **Process:** The cleaned dataset was imported into Power BI to build an interactive dashboard. This dashboard allows users to dynamically explore the data through various charts, maps, and filters.

-----

## 📊 A Note on Methodology: Why Median Over Average?

One of the most critical decisions in this analysis was the choice of a central tendency metric to represent the "typical" rental price. **This project exclusively uses the Median price, not the Average (Mean) price.** Here’s why:

The real estate market in Riyadh is incredibly diverse, with a wide range of properties. It includes everything from small, affordable studio apartments in older districts to ultra-luxurious, multi-million SAR villas in high-end neighborhoods.

  * **The Problem with Average (Mean):** The average is calculated by summing all prices and dividing by the number of properties. This makes it highly susceptible to **outliers** (i.e., extremely high or low values). A single, exceptionally expensive palace for rent can dramatically "pull" the average price upwards, giving a misleading impression that the typical rent is much higher than it actually is.

  * **The Strength of the Median:** The median is the middle value when all prices are sorted in ascending order. It represents the point where 50% of properties are cheaper and 50% are more expensive. By its nature, the median is **robust** and resistant to the influence of outliers. It provides a much more accurate and realistic picture of what a typical person should expect to pay for rent.

**In summary, to provide a trustworthy and non-skewed analysis of the Riyadh rental market, the median was chosen as the primary metric for price representation.**

-----

## 🚀 Dashboard Highlights

The interactive Power BI dashboard is the final output of this project. It empowers users to:

  * **Explore Geographically:** View an interactive map of Riyadh showing the median rental price for each district.
  * **Highest/Lowest:** see which High area or lowest area In Riyadh 
  * **Uncover Trends:** Compare different neighborhoods and property  to identify market trends and value opportunities.

Click the link at the top of this file to explore the live dashboard.
the file add so if you want to add or change in data 
