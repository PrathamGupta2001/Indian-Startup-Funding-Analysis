Indian Startup Funding Analysis (2020–2025)

A data analysis project focused on understanding the Indian startup funding ecosystem from 2020 to 2025. The project looks at funding trends, sectors, cities, funding stages, deal sizes, and investor activity to understand how the startup ecosystem changed over time.

The analysis combines Python, SQL, Excel, Power BI, and Tableau to clean the data, identify patterns, create visualizations, and present the findings through interactive dashboards.

📌 Project Overview

The main objective of this project is to answer questions such as:

- How has startup funding changed from 2020 to 2025?
- Which sectors received the most funding and had the highest number of deals?
- Which Indian cities have the strongest startup funding activity?
- Which funding stages are most common?
- Who are the most active investors?
- How does deal size vary across different sectors?
- Are there noticeable seasonal patterns in startup funding?
- How did the startup funding market recover after the 2022–2023 funding slowdown?

The project follows a complete data analysis workflow — from raw data cleaning and classification to analysis, visualization, and business insights.

📊 Key Findings

| Metric | Result |
|---|---|
| Total Funding | $28.09B |
| Total Deals | 1,100 |
| Peak Funding Year | 2021 |
| Top Sector | Ecommerce / D2C |
| Top Sector Deals | 205 |
| Median Deal Size | $1.1M |
| Post-Winter Recovery | 2024 showed a strong recovery |

 Major observations

- 2021 was the peak funding year, showing the strongest funding activity in the analyzed period.
- Funding activity declined during the startup funding slowdown that followed the 2021 peak.
- 2024 showed signs of recovery, with funding activity increasing compared with the previous period.
- Ecommerce / D2C was one of the strongest sectors by number of deals.
- Funding patterns differed considerably across sectors, cities, and funding stages.
- Deal sizes varied significantly depending on the sector and stage of funding.

🔍 Analysis Performed

 1. Data Collection & Preparation

The first step was to prepare the raw startup funding data for analysis.

The dataset contained information related to startup names, funding amounts, dates, sectors, cities, funding stages, and investors.

The data preparation process included:

- Reviewing the raw datasets.
- Removing duplicate and unnecessary records.
- Handling missing values.
- Standardizing dates and funding amounts.
- Cleaning inconsistent sector names.
- Preparing the data for SQL, Python, Excel, Power BI, and Tableau.
- Creating cleaned datasets that could be reused across different analysis tools.

This step was important because inconsistent categories and missing values could affect the accuracy of the final analysis.

2. Sector Reclassification

One of the challenges in the dataset was inconsistent or incorrect sector labeling.

For example, some startups were assigned to sectors that did not accurately represent their business.

To improve the quality of the analysis, a 3-layer sector reclassification approach was created.

Reclassification Process

| Layer | Method | Purpose |
|---|---|---|
| Layer 1 | Known company-name lookup | Correct known startup classifications |
| Layer 2 | Regex / pattern matching | Identify common sector patterns |
| Layer 3 | Investor-based inference | Handle remaining unclear classifications |

This helped reduce the number of startups incorrectly placed in the "Other" category and produced more meaningful sector level insights.

The reclassified dataset was then used for the remaining analysis.


📈 Funding Trend Analysis

The project analyzes how Indian startup funding changed between 2020 and 2025.

The analysis focuses on:

- Total funding by year
- Number of funding deals by year
- Year-over-year growth
- Peak funding periods
- Funding slowdown
- Post-winter recovery
- Long-term funding trends

This makes it easier to understand how the Indian startup ecosystem changed during different market conditions.


🏢 Sector Analysis

Sector level analysis was performed to identify which industries received the most funding and generated the highest number of deals.

The analysis includes:

- Total funding by sector
- Number of deals by sector
- Average deal size
- Median deal size
- Sector growth over time
- Sector-wise funding trends

Key Insight

E-commerce / D2C emerged as one of the strongest sectors by deal activity, with approximately 205 deals in the analyzed dataset.


💰 Funding Stage Analysis

The project also looks at how funding is distributed across different startup funding stages.

Examples include:

- Seed
- Pre-Series A
- Series A
- Series B
- Series C
- Later stage funding
- Other funding categories

This analysis helps understand whether startups are receiving funding primarily during their early stages or at more mature stages.


🌆 City-wise Analysis

Startup funding was also analyzed based on location.

The analysis looks at:

- Funding by city
- Number of deals by city
- Average deal size by city
- Major startup hubs
- City-wise funding trends

This helps identify the Indian cities that have the strongest startup funding ecosystems.


👥 Investor Analysis

The project also analyzes investor activity to identify the most active investors.

The analysis includes:

- Investors with the highest number of deals
- Investor activity across sectors
- Investor participation over time
- Comparison of active investors

This provides a view of which investors were most frequently involved in startup funding rounds.

📦 Deal Size Analysis

Deal size was analyzed across sectors and funding stages.

The analysis includes:

- Minimum deal size
- Maximum deal size
- Average deal size
- Median deal size
- Deal size distribution
- Sector-wise deal size comparison

The median deal size was approximately $1.1M, providing a better representation of the typical deal than the average alone because very large funding rounds can heavily influence the average.


🔄 Sector × Funding Stage Analysis

A cross-analysis was performed between startup sectors and funding stages.

This helps answer questions such as:

- Which sectors receive more early-stage funding?
- Which sectors attract larger later-stage rounds?
- How does funding stage distribution differ between industries?

This analysis provides a more detailed view than looking at sectors or funding stages individually.


📅 Seasonality Analysis

Monthly and quarterly funding patterns were also explored.

The purpose was to identify whether startup funding activity follows any noticeable seasonal pattern.

The analysis looks at:

- Monthly funding trends
- Quarterly funding trends
- Number of deals over time
- High and low funding periods


🐍 Python Analysis

Python was used as one of the main tools for data cleaning, exploration, and analysis.

Main tasks performed using Python:

- Data cleaning
- Missing-value handling
- Data transformation
- Sector reclassification
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Trend analysis
- Data visualization
- Exporting analysis-ready datasets

Main Python Libraries

- Pandas – Data manipulation and analysis
- Matplotlib – Data visualization
- Seaborn – Statistical visualizations
- OpenPyXL – Excel file generation
- Regex – Sector classification and pattern matching

The main analysis notebook is available in the `/notebooks` folder.


🗄️ SQL Analysis

SQL was used to perform structured analysis on the cleaned startup funding data.

The SQL analysis covers:

- Year-wise funding analysis
- Sector-wise funding
- Funding stage distribution
- City-wise analysis
- Investor analysis
- Deal size analysis
- Aggregations and comparisons
- Trend-based analysis
