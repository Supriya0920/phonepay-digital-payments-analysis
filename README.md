PhonePe Digital Payments Analysis (2018–2021)
This project performs an in-depth analysis of *PhonePe digital payment trends* across Indian states and districts between *Q1 2018 and Q2 2021*.  
It explores how *transactions, users, demographics, and device usage* evolve over time to understand *digital adoption patterns in India*.

Project Overview
PhonePe, one of India’s leading fintech platforms, provides detailed data on transactions, users, and device usage across regions.  
This project uses that dataset to:
- Analyze transaction *volume and value trends* by state and year.
- Identify *top-performing states and districts*.
- Examine *device brand preferences* among users.
- Correlate *population and user adoption* to understand penetration.
- Explore *demographic and behavioral factors* driving digital growth.Dataset Details

The data was provided in a multi-sheet Excel file containing:
| Dataset | Description |
|----------|--------------|
| *State_Txn and Users* | Total transactions, transaction amount, and users at state level |
| *State_TxnSplit* | Breakdown of transaction types (Recharge, P2P, Merchant, etc.) |
| *State_DeviceData* | Number of registered users by device brand |
| *District_Txn and Users* | Transaction and user data at district level |
| *District_Demographics* | Population, area, density, and other demographic details |
Tasks & Analysis Performed

Task 1 – Data Loading & Understanding*
- Loaded all datasets from Excel using pandas.
- Checked structure, statistics, data types, and missing values.
- Counted total states and districts; identified the state with most districts.

Task 2 – Exploratory Data Analysis (EDA)*
- Transaction trends over years and quarters.
- Top 5 and bottom 5 states by transaction volume and average transaction value (ATV).
- Device brand usage distribution.
- District with highest population per state (visualized via bar chart).
- App usage trends by state and time period.

Task 3 – Data Quality Checks*
- Verified data consistency between *state* and *district* level datasets.
- Detected and highlighted mismatches in totals.

Task 4 – Data Merging & Advanced Analysis*
- Merged demographic and transaction datasets.
- Calculated *user-to-population ratio* for each state.
- Correlated *population density* with transaction volume.
- Computed *average transaction amount per user* and device usage ratios.

Task 5 – Data Visualization*
- Line plots for transaction trends.
- Pie charts for transaction type distributions.
- Column charts and scatter plots for population & correlation analysis.

Task 6 – Insights and Conclusions*
Key findings:
- States like *Maharashtra, Karnataka, and Andhra Pradesh* lead in total transactions and digital penetration.
- High correlation between *population density and transaction volume*.
- Device usage dominated by *Xiaomi, Samsung, and Vivo*.
- Average Transaction Value (ATV) shows urban–rural economic differences.
- *Steady growth* in app usage and transactions over time, showing increased adoption of UPI-based payments.

Folder Structure
PhonePe Analysis Project
├── phonepe_analysis.ipynb # Main analysis notebook
├── phonepe-pulse_raw-data.xlsx # Source dataset
├── outputs/ # CSV results (ATV, user-population ratio, etc.)
├── plots/ # All generated plots and charts
└── README.md # Project documentation

Tools & Technologies
- Python 3.x
- Jupyter Notebook
- Pandas,NumPy,Matplotlib
- Git and GitHub for version control
Key Insights Summary
 Category / Observation
| Top Transaction States | Maharashtra, Karnataka, Andhra Pradesh, Telangana, Tamil Nadu |
| Highest Average Transaction Value (ATV)| Delhi, Maharashtra, Gujarat, Kerala |
| Most Used Devices | Xiaomi, Samsung, Vivo |
| Strongest Correlation | Population density ↔ Transaction volume |
| Trend | Continuous year-over-year growth in digital payments |

Conclusion

This analysis demonstrates the rapid expansion of *digital payment ecosystems* in India, highlighting how demographic and technological factors shape user adoption.  
The findings can guide *policy makers, **fintech strategists, and **marketers* in understanding consumer payment behavior and optimizing regional digital initiatives.
