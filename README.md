# Lung Cancer Surveillance and Outcomes Analysis Using Global Data for Local Insights

Author: **Nathan Rotich**

## Installation
In the project directory, you can run:

bash
Copy
Edit
git clone https://github.com/<YOUR-USERNAME>/Gen-Data-analysis.git
cd lung-cancer-data-analysis
## For data exploration:

Open the dataset CSV files using Excel 2021.


Open the Tableau dashboards (2025.1 version) for data visualization.

## Inspiration
AMPATH and similar healthcare networks in Kenya face urgent challenges in early lung cancer detection, screening coordination, and treatment equity.
This project seeks to close these gaps by analyzing global and individual-level data, offering actionable insights for targeted interventions—especially for underserved regions like western Kenya.

We wanted to create a backend-focused, data-driven tool that supports clinicians, researchers, and policy-makers with stratified metrics, survival analysis, and resource prioritization recommendations.

## What it does
Calculates health indicators: average survival years, diagnosis rates, early detection rates.

Stratifies outcomes by gender, smoking status, region, and age groups.

Compares Kenya-specific data with global benchmarks (GLOBOCAN (**Global Cancer Observatory**), SEER(**Surveillance, Epidemiology, and End Results.**).

Maps regional lung cancer burdens for resource allocation insights.

Identifies screening gaps among high-risk populations (e.g., older smokers).

Analyzes treatment patterns (surgery vs. radiotherapy) across genders and regions.

## How we built it
Excel 2021 for initial cleaning, parsing, and calculation.

Tableau 2025.1 for creating powerful, interactive visual dashboards.

Git/GitHub for version control and collaboration.

## Program Structure
Analytical Features:

Health Indicators Dashboard

Treatment Trends Explorer

Benchmark Comparison Charts

### Data Visualization Choices:

Health Indicators → Summary KPIs

Gender Prevalence → Vertical Bar Charts

Smokers vs Non-Smokers Diagnosis → Side-by-Side Bars

Smoking Habits by Age → Stacked Bar Charts

Diagnosis Stage Deviations → Horizontal Bars

Regional Prevalence → Interactive Maps

## Challenges we ran into
Fragmented global vs. regional data integration.

Limited local lung cancer registry data for Kenya.

Balancing technical complexity of Tableau visuals with accessibility for non-experts.

Raising stakeholder awareness on the importance of data-driven cancer program design.

## Accomplishments we're proud of
Built a  modular analysis pipeline combining  Excel, and Tableau.

Designed intuitive visuals that can be understood by clinical and non-clinical users.

Highlighted specific gaps in Kenya’s lung cancer early detection efforts with actionable suggestions.

## What we learned
Advanced data cleaning and normalization techniques.

Stratified health data modeling for public health use cases.

How to integrate global benchmarks into local analyses.

Using Tableau to simplify complex, multi-dimensional data for strategic decision-making.

## What's next
Real-Time Registry: Integrate OpenMRS for automatic updates.

Mobile/Tableau Mobile Dashboards: Enhance accessibility across devices.

Policy Toolkit Generator: Auto-create county-level policy briefs.

Predictive Modeling: Forecast trends using machine learning.

Global Comparative Analysis: Expand across Sub-Saharan datasets.

## Want to contribute?
If you would like to contribute to this project, please first read the Code of Conduct and Contributing Guidelines.

### Pre-requisites
Excel 2021

Tableau 2025.1

Git and GitHub account

### Project setup & contribution steps
Fork the project on GitHub.

Clone it locally:

bash
Copy
Edit
git clone https://github.com/<YOUR-USERNAME>/Gen-Data-analysis.git
cd lung-cancer-data-analysis
Create a new branch:

bash
Copy
Edit
git checkout -b fix-issue-<ISSUE-NUMBER>
Make your changes in:

SQL queries

Excel processing files

Tableau dashboard (.twbx files)

Commit and push:

bash
Copy
Edit
git status  
git add .  
git commit -m "feat/data-analysis:  Added risk stratification by smoking status"
git push origin fix-issue-<ISSUE-NUMBER>
Submit a pull request!
