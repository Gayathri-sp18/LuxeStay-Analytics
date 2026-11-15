<h1 align="center">LuxeStay Analytics</h1>

<p align="center">
  <em>Discovering the Story Behind Every Booking</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analytics-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Analysis-76B900?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## ✨ Project Overview

LuxeStay Analytics is a Python-based data analytics project focused on exploring hotel booking data to uncover meaningful patterns and insights within the hospitality industry.

The project examines booking behaviour, customer preferences, cancellation patterns, seasonal demand, and pricing indicators across City Hotels and Resort Hotels.

Using Python libraries, the raw dataset is cleaned, transformed, and analyzed through data preprocessing, feature engineering, statistical techniques, and exploratory data analysis (EDA).

The goal is to turn raw booking records into meaningful information that supports data-driven hotel management and business decisions.

## 🎯 Project Objectives

- 🏨 Analyze booking patterns across City Hotels and Resort Hotels.
- 📊 Examine monthly booking trends and seasonal demand.
- 🔍 Understand booking cancellation patterns.
- 👥 Explore customer behaviour and market segments.
- 💰 Analyze Average Daily Rate (ADR) and pricing indicators.
- 📈 Identify relationships between numerical variables.
- 🧹 Clean and transform raw data into an analysis-ready dataset.
- 💡 Generate meaningful insights to support business decisions.

## 📂 Dataset Overview

| Attribute | Details |
|---|---|
| Dataset Name | Hotel Booking Demand Dataset |
| Original Records | 119,390 |
| Original Columns | 32 |
| Hotel Categories | City Hotel & Resort Hotel |
| Data Period | 2015–2017 |
| File Format | CSV |

The dataset contains information about hotel bookings, arrival dates, guest details, length of stay, customer types, market segments, distribution channels, room preferences, cancellations, and Average Daily Rate (ADR).

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Interactive coding and analysis |

## 🔄 Data Analysis Workflow

### 01. Data Exploration
- Loaded and examined the dataset.
- Inspected dimensions, data types, and statistical summaries.
- Identified missing values and duplicate records.
- Examined unique values and categorical distributions.

### 02. Data Cleaning & Preprocessing
- Standardized column names.
- Removed exact duplicate records.
- Handled missing values and undefined categories.
- Converted date columns into appropriate formats.
- Identified and removed invalid records.
- Validated numerical and binary columns.

### 03. Outlier Detection
- Applied the Interquartile Range (IQR) method.
- Examined outliers in ADR, lead time, and stay duration.
- Created outlier indicators for further analysis.

### 04. Feature Engineering
Created meaningful features to support deeper analysis:

- Total Nights
- Arrival Quarter
- Arrival Day of the Week
- Weekend Arrival Indicator
- Children or Babies Indicator
- Room Changed Indicator
- Revenue Proxy

### 05. Exploratory Data Analysis (EDA)
- Monthly booking and cancellation analysis.
- Market segment analysis.
- Hotel-wise booking comparison.
- Customer-type cancellation analysis.
- GroupBy aggregations.
- Pivot table analysis.
- Correlation matrix and heatmap.

### 06. Data Validation & Export
- Checked remaining missing values.
- Verified duplicate records.
- Validated numerical and categorical values.
- Exported the cleaned dataset into CSV format.

## 📊 Key Analysis Areas

| Analysis | Focus |
|---|---|
| Hotel Performance | City Hotel vs Resort Hotel |
| Booking Trends | Monthly booking patterns |
| Cancellation Analysis | Booking cancellation behaviour |
| Customer Segmentation | Customer types and market segments |
| Pricing Analysis | Average Daily Rate (ADR) |
| Stay Duration | Weekday and weekend nights |
| Correlation Analysis | Relationships between numerical variables |

## 📁 Repository Structure

```text
LuxeStay-Analytics/
│
├── Hotel_Booking_Analysis.ipynb
├── hotel_bookings.csv
├── hotel_bookings_cleaned.csv
└── README.md
```

## 💡 Analytical Considerations

- The `revenue_proxy` feature is calculated using ADR multiplied by total nights. It represents an approximate booking value indicator, not verified realized revenue.
- Outliers are flagged for examination rather than automatically removed, as unusually high values may represent genuine bookings.
- Correlation identifies statistical relationships between variables but does not establish causation.

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/your-username/LuxeStay-Analytics.git
```

**2. Navigate to the project folder**

```bash
cd LuxeStay-Analytics
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**4. Launch Google Colab**

```bash
Google Colab
```

**5. Open and execute**

Open `Hotel_Booking_Analysis.ipynb` and run the cells sequentially.

## 👩‍💻 About the Author

**Gayathri S Pillai**

MBA Graduate | Aspiring Data Analyst

Passionate about data analytics, exploring patterns, and transforming raw data into meaningful business insights.

**Technical Skills:** Python | SQL | Excel | Power BI | Data Analytics

---

<p align="center">
  ⭐ <b>Thank you for visiting LuxeStay Analytics!</b>
  <br/>
  <i>Every booking tells a story. Let's uncover it through data.</i>
</p>
