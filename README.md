## Project Overview

This project analyses rental market trends across New South Wales (NSW) between 2021 and 2023 using Power BI. The objective was to identify changes in rental prices, compare dwelling types, and explore regional differences to support data-driven housing market insights.

---

## Business Questions

- How have rental prices changed from 2021 to 2023?
- Which dwelling types command the highest rents?
- How does Sydney compare with Regional NSW?
- Which postcodes have the highest median weekly rents?
- What rental growth trends can be observed across the market?

---

## Dataset

NSW Residential Rental Bond Lodgement Data (2021–2023)

Key fields:

- Lodgement Date
- Postcode
- Dwelling Type
- Bedrooms
- Weekly Rent

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Data Preparation

### Data Cleaning

- Removed incomplete and invalid records
- Standardised dwelling type categories:
  - F → Flat
  - H → House
  - T → Townhouse
  - O → Other
  - U → Unknown
- Corrected data types and field formats
- Merged 2021, 2022, and 2023 datasets into a new dataset

### Data Modelling

Created calculated columns and measures including:

- Year
- YearMonth
- Sydney vs Regional NSW classification
- Median Weekly Rent
- Rent Growth %
- Year-over-Year comparisons

---

## Dashboard Pages

### 1. Overview

Provides high-level market indicators and trends:

- Median Weekly Rent (2021–2023)
- Total Weekly Rent
- Rent Growth %
- Monthly Rent Trend

### 2. Property Analysis

Explores rental patterns by property characteristics:

- Rent by Dwelling Type
- Rent by Number of Bedrooms
- Bedroom × Dwelling Type Heatmap

### 3. Client-Faced Analysis

Supports decision-making through:

- Sydney vs Regional NSW comparison
- Median Rent by Postcode
- Geographic rent distribution

---

## Key Insights

- Median weekly rent increased from **$470** in 2021 to **$630** in 2023.
- Townhouses recorded the highest rental growth during the analysis period.
- Sydney consistently maintained higher rental prices than Regional NSW.
- Rental growth accelerated significantly after 2022.
- Larger properties generally achieved higher weekly rents across all dwelling types.

---

## Repository Structure

```text
├── README.md
├── NSW_Rental_Dashboard.pbix
├── screenshots/
│   ├── overview.png
│   ├── property_analysis.png
│   └── client_faced_analysis.png
└── data/
    ├── NSW_Lodgement_2021.xlsx
    ├── NSW_Lodgement_2022.xlsx
    └── NSW_Lodgement_2023.xlsx
```

---

## Dashboard Preview

### Overview Dashboard

<img width="2880" height="1700" alt="Overview" src="https://github.com/user-attachments/assets/3ad88eb2-196a-49c2-8ea0-90ef43e2c38a" />

### Property Analysis Dashboard

<img width="2880" height="1700" alt="Property_Analysis" src="https://github.com/user-attachments/assets/5bf363dc-7e8f-4f02-867f-dea250f0cf0e" />

### Client-Faced Analysis Dashboard

<img width="2880" height="1696" alt="Client-Faced_Analysis" src="https://github.com/user-attachments/assets/6b7dedb3-517f-41f4-99e2-01b08dec144c" />

## Limitations & Future Research

### Limitations

- The analysis is based solely on NSW Residential Rental Bond Lodgement data.
- External market factors such as interest rates, inflation, migration, housing supply, and vacancy rates were not included.
- Sydney and Regional NSW classifications were derived from postcode-based assumptions and may not fully align with official geographic boundaries.

### Future Research

Future analysis could incorporate additional datasets to explore potential drivers of rental market changes, including:

- Reserve Bank of Australia (RBA) cash rate data
- Property sales transaction data
- Population and migration statistics
- Housing supply and vacancy rate indicators
- Residential Rental Bond Refund datasets

This would enable a more comprehensive investigation of the factors influencing rental price growth across NSW.
