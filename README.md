# EconRebound: Tracking America's Economic Resilience (2020-2024)

## Project Overview
This repository contains a comprehensive analysis of U.S. economic indicators from Q1 2020 through Q4 2024, tracking the economy's journey through the COVID-19 pandemic, subsequent recovery, and stabilization. The analysis examines the relationships between key economic metrics including GDP, Consumer Price Index (CPI), Personal Consumption Expenditures (PCE), and unemployment-adjusted CPI.

## Dataset
The dataset includes quarterly data from 2020-2024 covering:
- Gross Domestic Product (GDP in billions USD)
- Consumer Price Index (CPI)
- Personal Consumption Expenditures (PCE in billions USD)
- Unemployment-adjusted CPI (CPI_U)
  
## Source
- (Federal Reserve Economic Data) https://fred.stlouisfed.org/
- (U.S. Bureau of Labor Statistics) https://www.bls.gov/data/home.htm
- (Bureau of Economic Analysis) https://www.bea.gov/data/gdp

## Key Findings
- **Pandemic Impact & Recovery**: Sharp 9.11% GDP contraction in Q2 2020 followed by a V-shaped recovery
- **Growth Phases**: Exceptional growth in 2021 (14% year-over-year) followed by normalization to 5-7% in 2022-2024
- **Inflation Trends**: Peak inflation of 7.10% in 2022 moderating to 2.72% by 2024
- **Economic Correlations**: Nearly perfect correlation between GDP and PCE (1.00) confirming consumer spending as the primary economic driver
- **Price-Growth Relationship**: For each 1% increase in CPI, GDP increased by approximately $263 billion


## Technical Implementation
- **Data Processing**: Python with pandas for data manipulation
- **Statistical Analysis**: NumPy and SciPy for correlation analysis
- **Visualizations**: Matplotlib and Seaborn for chart generation

## Key Economic Phases Identified
1. **Pandemic Contraction** (Q2 2020): Sharp GDP and consumer spending decline
2. **Rapid Recovery** (Q3 2020 - Q4 2020): Quick rebound to pre-pandemic levels
3. **Growth & Inflation** (2021 - early 2022): Strong growth with accelerating inflation
4. **Normalization** (late 2022 - 2024): Moderate, steady growth with inflation tapering
