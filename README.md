# Lung Cancer Data Analysis and Screening Insights Tool
## Author : Nathan Rotich

## Project Summary
This is a Data analytics project that processes combined individual- and country-level lung cancer data. It uses tools like Excel, SQL, and Tableau to calculate health indicators such as survival years, diagnosis rates, detection stages, and treatment trends. The project highlights disparities in diagnosis and survival based on gender, age, region, and smoking status. The tool aims to support cancer care programs—especially in regions like western Kenya—by offering data-driven recommendations for early detection, targeted screening, and resource allocation.

## Problem Statement
What problem will your Python project solve?

AMPATH, **(Academic Model Providing Access to Healthcare;it is a partnership between Moi University and Moi Teaching and Referral Hospital in Kenya and a consortium of North American academic health centers, led by Indiana University. AMPATH aims to deliver comprehensive healthcare services, conduct research, and provide training and capacity building, particularly in HIV/AIDS and chronic disease management across western Kenya.)** and similar health networks in Kenya face major challenges with late-stage lung cancer detection, lack of screening programs, poor data coordination, and unequal resource access. This project uses global benchmarking and granular and non-granular data analysis to identify gaps in early diagnosis and treatment and provides actionable insights to bridge them.

## Why is this solution needed?
Supports AMPATH in building data-driven cancer registries.
Helps health facilities identify high-risk populations for screening.
Enables policymakers and donors to visualize gaps in early-stage detection and survival.
Promotes better resource deployment in underserved areas like rural western Kenya.

## Who will use this program?
Public health researchers and analysts
Cancer care program managers (e.g., AMPATH)
Oncologists and radiologists
Policy-makers in health ministries
Global health funders and donors

## Technical Details
Excel 2021 version

Tableau 2025.1

## Core Concepts Used:

File handling and data parsing

Basic statistical operations

Data visualization using Tableau (external)

Integration with SQL queries

### Development Tools
Editor: VS Code

Version Control: Git/GitHub

Visualization: Tableau

Database: SQL (SQLite or MySQL)

## Program Structure
### Core Features
1. Health Indicators Dashboard and Stratified Metrics
Calculates average survival years, early detection rate, and diagnosis stage.

Stratifies data by gender, age, stage, smoking status, and region.

3. Comparison with Global Benchmarks
Uses GLOBOCAN (**Global Cancer Observatory**) , SEER (**Surveillance, Epidemiology, and End Results**), and peer-reviewed studies to compare national and local metrics.

4. Risk Stratification and Screening Gap Analysis
Highlights differences in detection and diagnosis by smoking status and age group.

Shows missed screening opportunities in high-risk groups (e.g., smokers aged 65–70).

6. Treatment Pattern Analysis
Compares gender differences in treatment modalities (surgery vs. radiotherapy).

Maps treatment choices across stages and regions.

8. Regional Burden Mapping
Identifies hotspots like Ethiopia and South Asia as highest-burden areas.

Offers insights for targeted interventions in similar regions like western Kenya.

## User Interface
This is a non-GUI project only  focused on backend data analysis.
However:
Tableau dashboards provide a visual front-end for all stakeholders .
## Project Timeline
Day	Programming Tasks	Status
_________________________________________
1 |	Data collection and cleaning | Done

2 |	SQL query development |	Done

3 |	Health Indicators calculation |	Done

4	| Benchmark integration |	Done

5	| Tableau dashboard creation |	In Progress

6	| Report writing and packaging	| Not Started
## Data Source 
I used Lung Cancer Risk  from 25 Countries dataset from Kaggle by Aiza Zeeshan.

I used global data because  Kenya Cancer centers  lacks comprehensive cancer registries. Global datasets help fill critical gaps in epidemiological insights.

Less cleaning was needed ,the dataset had no blank spaces and the population size was divided by a million for consistency in Scale for Visualization.
### Data visualization
Reasoning Behind Data Visualization Choices
1. Average Survival Years, Diagnosis Rate, Early Detection Rate → Health Indicators
Why: These are high-level summary metrics critical for tracking progress and setting targets in public health.

Tool: Designed as health indicators (similar to KPIs in business) to quickly communicate performance and highlight gaps.

2. Lung Cancer Prevalence by Gender → Vertical Bar Charts
Why: Clearly compares prevalence rates between male and female groups.

Tool: Vertical bar charts offer a simple, intuitive visual comparison of categorical data.

3. Diagnosis Among Smokers vs Non-Smokers → Side-by-Side Vertical Bar Charts
Why: Highlights contrast in lung cancer incidence between smoking statuses.

Tool: Side-by-side bars allow for direct comparison within shared categories, improving clarity.

4. Active Smokers Across Age Groups → Stacked Bar Charts
Why: Shows distribution of smoking habits across age brackets while preserving total population structure.

Tool: Stacked bars reveal both individual age group contributions and overall trends.

5. Diagnosis Stage Deviation from Stage I → Horizontal Bar Charts
Why: Illustrates how far other stages deviate from early detection baseline (Stage I).

Tool: Horizontal bars make it easier to visualize positive/negative deviation side by side for emphasis.

6. Prevalence by Country → Map Visualization
Why: Communicates geographic disparities in lung cancer prevalence at a glance.

Tool: Map views are ideal for representing spatial data, drawing attention to regional patterns and hotspots.





## Data Storage
CSV files for raw patient records.

SQL database for country-level metrics.

Tableau for interactive dashboards.


### Testing Strategy
Unit Testing:
Verify correct diagnosis rate and survival year calculations.

Ensure proper functioning of filtering by gender, stage, and region.

### User Testing:
Use test cohorts from AMPATH data to simulate regional and demographic outputs.

Review outputs with domain experts for clinical relevance.

## Sample Usage
Input Scenario:

Smoking status: Ever-smoker

Age: 68

Region: Western Kenya

Expected Output:

Average survival years: 5 years & 6  months

Early detection rate: 28%

Stage IV deviation from Satge I: +15.5%

## Recommendation:
Expand LDCT screening and launch smoking cessation campaigns.

Potential Challenges

## Challenge faced
Fragmented data sources	Integrate datasets via a unified SQL schema

Missing regional health data	Collaborate with AMPATH for local records

Complex visualizations in Tableau	Create simplified views for non-technical users

Limited stakeholder awareness	Integrate insights into AMPATH Oncology ECHO

## Future Improvements
Real-Time Registry: Integrate with OpenMRS for live data updates.

Mobile Dashboards: Convert visual outputs into mobile/tablet formats.

Policy Toolkit: Auto-generate reports for counties and ministries.

Predictive Modeling: Add machine learning to forecast case trends.

Global Integration: Compare trends across Sub-Saharan countries.



