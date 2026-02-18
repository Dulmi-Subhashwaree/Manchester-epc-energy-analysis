Energy Performance Analysis of Manchester Local Authorities
Overview

This project analyzes Energy Performance Certificate (EPC) data for residential properties across Greater Manchester using SQL Server and visualizes insights through an interactive Power BI dashboard. The analysis highlights energy efficiency trends, CO₂ emissions, energy costs, and improvement potential to support sustainability and policy decision-making.

Dataset

The project uses two EPC datasets: Certificates and Recommendations, which provide detailed property-level energy performance data and suggested efficiency improvements.

Source: UK Domestic EPC Open Data Portal

Format: CSV

Coverage period: 2014–2024

Project Components
1. SQL Analysis

SQL Server (T-SQL) was used for data cleaning, transformation, and integration.

Key tasks include:

Cleaning and standardizing EPC data

Removing duplicates and handling missing values

Integrating certificates and recommendations using LMK_KEY

Preparing analytical tables for Power BI

2. Power BI Dashboard

The Power BI .pbix file presents interactive visualizations including:

Current vs potential energy efficiency

CO₂ emissions by property type and over time

Heating and lighting cost analysis

Recommendation frequency and improvement potential

Geospatial distribution of EPC certificates

🔗 Power BI Dashboard (PBIX):
👉 https://drive.google.com/your-link-here

3. Report

A detailed PDF report covering:

Data preparation and SQL methodology

Power BI modeling and DAX measures

Results analysis, key findings, and recommendations

Key Findings

85% of properties show potential for energy efficiency improvement

Average potential efficiency exceeds current efficiency by ~12 points

Heating costs are the primary contributor to energy expenses and CO₂ emissions

Houses represent the largest opportunity for mass retrofitting

Park Homes are identified as the least energy-efficient property type

Limitations

EPC data does not cover all properties in Manchester

Analysis is based on lodged EPC records, not real-time energy usage

Socio-economic factors were not included

Findings may not fully represent post-2024 conditions

Recommendations

Prioritize heating and insulation upgrades to reduce energy costs and emissions

Implement targeted retrofit programs for low-efficiency property types

Support policy-driven energy efficiency initiatives at the local authority level

Use interactive dashboards for ongoing monitoring and planning

Challenges

Handling large datasets with inconsistent formats

Cleaning corrupted values and duplicate records

Designing clear and meaningful Power BI visualizations

Interpreting efficiency gaps across diverse property types

Conclusion

The analysis reveals a substantial opportunity to improve residential energy efficiency across Greater Manchester. By combining SQL-based data processing with Power BI analytics, the project demonstrates how public EPC data can be transformed into actionable insights for sustainable urban planning and energy policy.

Author

Dulmi Subhashwaree
BSc in Applied Data Science Communication (UG)

License

This project is for educational purposes only.
