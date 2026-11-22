 <h1 align="center">LuxeStay Analytics</h1>

<p align="center"><em>Discovering the Story Behind Every Booking</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-8B1E3F?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-6D214F?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-B76E79?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Data%20Analysis-9B6A73?style=for-the-badge" />
</p>

---

## ✦ Project Overview

**LuxeStay Analytics** is a Python-based data analysis project that explores hotel booking data from City Hotels and Resort Hotels.

The project focuses on understanding booking patterns, customer behaviour, cancellation trends, seasonal demand and revenue-related indicators through data cleaning, exploratory data analysis (EDA), statistical summaries and visualizations.

The analysis aims to uncover meaningful patterns in hotel bookings and present them through clear, informative visualizations.

## ✦ Project Objectives

- Analyse booking trends across different hotel types.
- Understand customer booking behaviour and preferences.
- Identify cancellation patterns across market segments.
- Explore seasonal booking trends and demand.
- Examine Average Daily Rate (ADR) and length of stay.
- Identify relationships between numerical variables.
- Present insights through meaningful visualizations.

## ✦ Dataset

**Hotel Booking Demand Dataset**

- Original records: 119,390
- Original columns: 32
- Hotel categories: City Hotel and Resort Hotel
- Data period: 2015–2017

The dataset contains information about reservation dates, customer types, booking channels, lead time, length of stay, room preferences, cancellation status and Average Daily Rate (ADR).

## ✦ Tools & Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly Express | Interactive visualizations |
| Squarify | Treemap visualization |
| Google Colab | Development environment |

## ✦ Data Cleaning & Preprocessing

The dataset was examined and prepared before performing the analysis.

Key steps included:

- Initial dataset inspection and structure analysis.
- Standardizing column names and removing whitespace.
- Identifying and removing exact duplicate records.
- Handling missing values and undefined categories.
- Converting date columns into appropriate formats.
- Validating guest counts, ADR and booking durations.
- Identifying outliers using the IQR method.
- Performing business logic and data consistency checks.

## ✦ Feature Engineering

Additional features were created to support deeper analysis:

- `total_guests` – Total number of guests.
- `total_nights` – Total length of stay.
- `arrival_date` – Combined arrival date.
- `arrival_quarter` – Quarter of arrival.
- `arrival_day_of_week` – Day of arrival.
- `is_weekend_arrival` – Identifies weekend arrivals.
- `has_children_or_babies` – Indicates bookings with children or babies.
- `room_changed` – Identifies room changes.
- `revenue_proxy` – Approximate revenue indicator calculated using ADR × total nights.

## ✦ Exploratory Data Analysis & Visualizations

A total of **12 visualizations** were created to explore different aspects of hotel booking data.

### Visualization Gallery

<p align="center"><strong>01 — Monthly Booking Trends</strong></p>
<p align="center"><img src="images/monthly_booking_trends.png" width="90%" alt="Monthly Booking Trends" /></p>

<p align="center"><strong>02 — Booking Distribution by Hotel Type</strong></p>
<p align="center"><img src="images/hotel_distribution.png" width="90%" alt="Booking Distribution by Hotel Type" /></p>

<p align="center"><strong>03 — Cancellation Rate by Hotel Type</strong></p>
<p align="center"><img src="images/cancellation_hotel_type.png" width="90%" alt="Cancellation Rate by Hotel Type" /></p>

<p align="center"><strong>04 — Cancellation Rate by Market Segment</strong></p>
<p align="center"><img src="images/cancellation_market_segment.png" width="90%" alt="Cancellation Rate by Market Segment" /></p>

<p align="center"><strong>05 — Bookings by Distribution Channel</strong></p>
<p align="center"><img src="images/distribution_channel_treemap.png" width="90%" alt="Bookings by Distribution Channel" /></p>

<p align="center"><strong>06 — ADR Distribution</strong></p>
<p align="center"><img src="images/adr_distribution.png" width="90%" alt="ADR Distribution" /></p>

<p align="center"><strong>07 — ADR Comparison by Hotel Type</strong></p>
<p align="center"><img src="images/adr_hotel_comparison.png" width="90%" alt="ADR Comparison by Hotel Type" /></p>

<p align="center"><strong>08 — Length of Stay Distribution</strong></p>
<p align="center"><img src="images/length_of_stay.png" width="90%" alt="Length of Stay Distribution" /></p>

<p align="center"><strong>09 — Top 10 Countries by Booking Count</strong></p>
<p align="center"><img src="images/top_countries.png" width="90%" alt="Top 10 Countries by Booking Count" /></p>

<p align="center"><strong>10 — Lead Time vs ADR</strong></p>
<p align="center"><img src="images/lead_time_vs_adr.png" width="90%" alt="Lead Time vs ADR" /></p>

<p align="center"><strong>11 — Customer Type Distribution by Hotel</strong></p>
<p align="center"><img src="images/customer_type_distribution.png" width="90%" alt="Customer Type Distribution by Hotel" /></p>

<p align="center"><strong>12 — Correlation Analysis</strong></p>
<p align="center"><img src="images/correlation_heatmap.png" width="90%" alt="Correlation Heatmap" /></p>

## ✦ Key Observations

- **Hotel Booking Distribution:** City Hotels accounted for approximately 61.1% of bookings, while Resort Hotels accounted for 38.9%.
- **Cancellation Trends:** City Hotels recorded a higher cancellation rate (30.10%) compared with Resort Hotels (23.48%).
- **Market Segment:** Online Travel Agents recorded the highest cancellation rate among the major market segments, at approximately 35.38%.
- **Distribution Channels:** Travel Agents and Tour Operators contributed approximately 79.1% of bookings.
- **ADR Comparison:** City Hotels had a higher median ADR of 105.30 compared with Resort Hotels at 79.50.
- **Length of Stay:** Resort Hotel guests stayed longer on average than City Hotel guests.
- **Country-wise Bookings:** Portugal recorded the highest number of bookings among the countries represented.
- **Customer Type:** Transient customers formed the largest customer category for both hotel types.
- **Correlation:** Lead time showed a positive correlation with cancellations, although the relationship was relatively weak.

## ✦ Analytical Considerations

- Outliers were identified using the IQR method and flagged rather than automatically removed.
- The `revenue_proxy` feature represents an approximation and not a verified final booking payment.
- A random sample of 5,000 records was used for the Lead Time vs ADR scatter plot to improve visualization.
- Correlation indicates association and does not establish causation.

## ✦ Repository Structure

```text
LuxeStay-Analytics/
│
├── Hotel_Booking_Analysis.ipynb
├── hotel_bookings_cleaned.csv
├── README.md
│
└── images/
    ├── monthly_booking_trends.png
    ├── hotel_distribution.png
    ├── cancellation_hotel_type.png
    ├── cancellation_market_segment.png
    ├── distribution_channel_treemap.png
    ├── adr_distribution.png
    ├── adr_hotel_comparison.png
    ├── length_of_stay.png
    ├── top_countries.png
    ├── lead_time_vs_adr.png
    ├── customer_type_distribution.png
    └── correlation_heatmap.png
```

## ✦ How to Run the Project

1. Clone or download this repository.
2. Open `Hotel_Booking_Analysis.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the `hotel_bookings.csv` dataset.
4. Install the required libraries if they are not already available.
5. Run the notebook cells sequentially to perform the analysis.

---

👩‍💻 About the Author

Gayathri S Pillai

MBA Graduate | Aspiring Data Analyst

Passionate about data analytics, exploring patterns, and transforming raw data into meaningful business insights.

Technical Skills: Python | SQL | Excel | Power BI | Data Analytics

<p align="center">
  ⭐ <b>Thank you for visiting LuxeStay Analytics!</b>
  <br/>
  <i>Every booking tells a story. Let's uncover it through data.</i>
</p>
