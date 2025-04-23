# Lung Cancer Data Analysis and Screening Insights Tool

## Project Summary
This project is a Python-based analytical tool that processes combined individual- and country-level lung cancer data. It uses tools like Excel, SQL, and Tableau to calculate key performance indicators (KPIs) such as survival years, diagnosis rates, detection stages, and treatment trends. The project highlights disparities in diagnosis and survival based on gender, age, region, and smoking status. The tool aims to support cancer care programs—especially in regions like western Kenya—by offering data-driven recommendations for early detection, targeted screening, and resource allocation.

## Problem Statement
What problem will your Python project solve?
AMPATH and similar health networks in Kenya face major challenges with late-stage lung cancer detection, lack of screening programs, poor data coordination, and unequal resource access. This project uses global benchmarking and granular data analysis to identify gaps in early diagnosis and treatment and provides actionable insights to bridge them.

## Why is this solution needed?
Supports AMPATH in building data-driven cancer registries.

Helps health facilities identify high-risk populations for screening.

Enables policymakers and donors to visualize gaps in early-stage detection and survival.

Encourages informed decision-making based on real patient and regional data.

Promotes better resource deployment in underserved areas like rural western Kenya.

## Who will use this program?
Public health researchers and analysts

Cancer care program managers (e.g., AMPATH)

Oncologists and radiologists

Policy-makers in health ministries

Global health funders and donors

## Technical Details
Python Components
Python Version:
Python 3.13

## Core Concepts Used:

File handling and data parsing

Basic statistical operations

Data visualization using Tableau (external)

Integration with SQL queries

Basic Python Libraries
pandas for data analysis

matplotlib or seaborn for optional plotting

csv, json for file parsing

sqlite3 or similar for querying structured data

Development Tools
Editor: VS Code

Version Control: Git/GitHub

Visualization: Tableau

Database: SQL (SQLite or MySQL)

## Program Structure
### Core Features
1. KPI Dashboard and Stratified Metrics
Calculates average survival years, early detection rate, and diagnosis stage.

Stratifies data by gender, age, stage, smoking status, and region.

2. Comparison with Global Benchmarks
Uses GLOBOCAN, SEER, and peer-reviewed studies to compare national and local metrics.

3. Risk Stratification and Screening Gap Analysis
Highlights differences in detection and diagnosis by smoking status and age group.

Shows missed screening opportunities in high-risk groups (e.g., smokers aged 65–70).

4. Treatment Pattern Analysis
Compares gender differences in treatment modalities (surgery vs. radiotherapy).

Maps treatment choices across stages and regions.

5. Regional Burden Mapping
Identifies hotspots like Ethiopia and South Asia as highest-burden areas.

Offers insights for targeted interventions in similar regions like western Kenya.

## User Interface
This is a non-GUI tool focused on backend data analysis. However:

Tableau dashboards provide a visual front-end for stakeholders.

The tool can be extended with a Tkinter or Streamlit interface for local clinical use.

## Project Timeline

Day	Programming Tasks	Status
_________________________________________
1	Data collection and cleaning | Done
2	SQL query development |	Done
3	KPI calculation |	Done
4	Benchmark integration |	Done
5	Tableau dashboard creation |	In Progress
6	Report writing and packaging	| Not Started
Program Design
Functions and Classes Overview

## Data Storage
CSV files for raw patient records.

SQL database for country-level metrics.

Tableau for interactive dashboards.


Testing Strategy
Unit Testing:
Verify correct diagnosis rate and survival year calculations.

Ensure proper functioning of filtering by gender, stage, and region.

User Testing:
Use test cohorts from AMPATH data to simulate regional and demographic outputs.

Review outputs with domain experts for clinical relevance.

Project Delivery
Running the Program
Install Python 3.13, clone the repository, and run:

bash
Copy
Edit
python lung_cancer_analytics.py
Sample Usage
Input Scenario:

Smoking status: Ever-smoker

Age: 68

Region: Western Kenya

Expected Output:

Average survival years: 5.5

Early detection rate: 28%

Stage IV excess: +15.5%

Recommendation: Expand LDCT screening and launch smoking cessation campaigns.

Potential Challenges

## Challenge	Solution
Fragmented data sources	Integrate datasets via a unified SQL schema
Missing regional health data	Collaborate with AMPATH for local records
Complex visualizations in Tableau	Create simplified views for non-technical users
Limited stakeholder awareness	Integrate insights into AMPATH Oncology ECHO
Future Improvements
Real-Time Registry: Integrate with OpenMRS for live data updates.

Mobile Dashboards: Convert visual outputs into mobile/tablet formats.

Policy Toolkit: Auto-generate reports for counties and ministries.

Predictive Modeling: Add machine learning to forecast case trends.

Global Integration: Compare trends across Sub-Saharan countries.



