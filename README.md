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

###**Visualization Gallery**

<p align="center"><strong>01 — Monthly Booking Trends</strong></p>
<p align="center"><img width="1287" height="558" alt="Monthly Booking Trends" src="https://github.com/user-attachments/assets/1ad2f13d-ceea-4a4c-b6c8-b16f13ecad12" />

<p align="center"><strong>02 — Booking Distribution by Hotel Type</strong></p>
<p align="center"><img width="765" height="677" alt="Booking Distribution by Hotel Type" src="https://github.com/user-attachments/assets/7f401f34-993f-4ae8-a40d-1078ea5e0135" />



<p align="center"><strong>03 — Cancellation Rate by Hotel Type</strong></p>
<p align="center"><img width="748" height="537" alt="Bookings by Distribution Channel" src="https://github.com/user-attachments/assets/b2eb0d90-68d4-4fde-aef9-34f078c8ced6" />


<p align="center"><strong>04 — Cancellation Rate by Market Segment</strong></p>
<p align="center"><img width="775" height="438" alt="Cancellation Rate by Market Segment" src="https://github.com/user-attachments/assets/f3396749-42cf-4184-9768-c3560f360776" />


<p align="center"><strong>05 — Bookings by Distribution Channel</strong></p>
<p align="center"><img width="748" height="537" alt="Bookings by Distribution Channel" src="https://github.com/user-attachments/assets/585d5110-3768-45be-90a9-732f69a80789" />


<p align="center"><strong>06 — ADR Distribution</strong></p>
<p align="center"><img width="741" height="432" alt="ADR Distribution" src="https://github.com/user-attachments/assets/c9f9cf45-5ab1-4685-a3b9-987af76282fd" />


<p align="center"><strong>07 — ADR Comparison by Hotel Type</strong></p>
<p align="center"><img width="767" height="692" alt="ADR Comparison by Hotel Type" src="https://github.com/user-attachments/assets/4ba24034-c58e-4607-8cc5-af2e53e55679" />


<p align="center"><strong>08 — Length of Stay Distribution</strong></p>
<p align="center"><img width="773" height="607" alt="Length of Stay Distribution" src="https://github.com/user-attachments/assets/0cfc2da0-fc72-46f0-8807-b8eff608b065" />


<p align="center"><strong>09 — Top 10 Countries by Booking Count</strong></p>
<p align="center"><img width="987" height="600" alt="Top 10 Countries by Booking Count" src="https://github.com/user-attachments/assets/8e22ed39-7f03-4b50-92c3-f98a596bf2d7" />

<p align="center"><strong>10 — Lead Time vs ADR</strong></p>
<p align="center"><img width="766" height="421" alt="Lead Time vs ADR" src="https://github.com/user-attachments/assets/8811408b-f235-47cb-be37-e064d6e989b6" />


<p align="center"><strong>11 — Customer Type Distribution by Hotel</strong></p>
<p align="center"><img width="787" height="621" alt="Customer Type Distribution by Hotel" src="https://github.com/user-attachments/assets/41b178dc-cb2d-46d2-b07e-7716d36255e5" />


<p align="center"><strong>12 — Correlation Analysis</strong></p>
<p align="center"><img width="771" height="570" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/5ea83f13-3b9d-4b88-8a52-20d0992aab6a" />


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

👩‍💻 **About the Author**

Gayathri S Pillai

MBA Graduate | Aspiring Data Analyst

Passionate about data analytics, exploring patterns, and transforming raw data into meaningful business insights.

Technical Skills: Python | SQL | Excel | Power BI | Data Analytics

<p align="center">
  ⭐ <b>Thank you for visiting LuxeStay Analytics!</b>
  <br/>
  <i>Every booking tells a story. Let's uncover it through data.</i>
</p>
