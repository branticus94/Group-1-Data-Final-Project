![image](https://github.com/user-attachments/assets/3cd5e809-675c-4155-a39e-1158cee43a68)

# Societal Impacts of COVID-19: Data Analysis Project

# CFG Data Nano-Degree Group 1
# Group Members:
- Heledd Davies
- Natalie Ellis
- Hafsa Hussain
- Zenzi Mansaray
- Hayley Lawrence
- Lisa Franchetti
- Alexandra Howland

## Overview

This project investigates the societal impacts of the COVID-19 pandemic, focusing on critical areas such as misinformation, mental health, education, employment, and vaccine hesitancy. Through comprehensive data analysis, it aims to provide insights into how the pandemic reshaped society and offers recommendations for policymakers in health, education, and employment sectors.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Challenges and Achievements](#challenges-and-achievements)

---

## Introduction

### Research Questions
This project answers the question: **What were the societal impacts of the spread of COVID-19?** Key areas of focus include:
- The rise of misinformation (infodemic).
- Mental health challenges.
- Disruptions in school performance.
- Employment trends.
- Vaccine hesitancy and adoption patterns.

### Objectives
- Investigate the societal effects of the pandemic.
- Identify trends and correlations in key focus areas.
- Provide actionable insights for policymakers and other stakeholders.

---

## Features
- **Comprehensive Analysis**: Investigates diverse societal domains.
- **Data Integration**: Combines multiple datasets and API sources.
- **Visualisation**: Produces clear, informative charts and graphs.
- **Modular Design**: Structured codebase.

---

## Installation

1. Clone this repository:
   ```
   git clone git@github.com:branticus94/CFG-Group-1-Data-Final-Project.git
   ```

2. Install dependencies
   ```
   pip install -r requirements.txt
   ```
   
3. Add the following files from google drive to their respective location (these files were too large to upload to GitHub):
- [UKHSA Cases Data:](https://drive.google.com/file/d/15zuegbX43NG22VrHp8Wz6RC0ohlbZJ19/view?usp=sharing)
- [UKHSA Vaccine Data:](https://drive.google.com/file/d/1ata9dPfKjFPwAGGjA95-4aSEpvLctRfH/view?usp=sharing) 
```
1_raw_files
├── aaai_data
├── education_data
├── employment_data
├── esoc_data
├── ofcom_covid_data_xlsx
├── ons_education_survey
├── ons_labour_market_statistics
├── ons_vaccination_hesitancy
├── ukhsa_cases_data
|  └── CASES DATA GOES HERE
└── ukhsa_vaccine_data
  └──VACCINE DATA GOES HERE
```
- [USA covid_api_data](https://drive.google.com/file/d/1h0YqR7QheL56YCLhFKxcGBo4hvAVDwY7/view?usp=sharing)
```
4_integrated_csv_files
├── covid_19_api_data
|  └── USA file goes here
├── education_data
├── employment_data
├── nhs_data
├── ofcom_data
├── ons_api_data
├── ons_education
├── ons_labour_market_statistics
├── ukhsa_cases_data
├── ukhsa_mortality_data
└── ukhsa_vaccination_data
```
## Data Sources
The project utilises several data sources, namely:
- COVID-19 Statistics API: Global cases and vaccination data.
- UKHSA Fingertips API: Health data specific to the UK.
- ONS API: Employment and mental health statistics.
- ESOC COVID-19 Misinformation Dataset: Misinformation trends.
- OFCOM COVID-19 Survey Data: Media consumption and trust during the pandemic.

---

## Methodology:
### Framework
- ETL (Extract, Transform, Load):
  - Extract: Retrieve data from APIs and raw files.
  - Transform: Clean and preprocess data.
  - Load: Generate visualisations and reports.
- Focus Areas: Modular analysis for domains like misinformation, mental health, and education.

- Tools
  - Programming: Python with libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.
  - Version Control: Git and GitHub.
  - Project Management: Jira and Slack.

--- 

## Challenges and Achievements
### Challenges
- API rate limits causing slow response times.
- Cleaning inconsistencies in large, diverse datasets.
- Adapting to shifts in scope due to data availability.

### Achievements
- Successfully integrated and processed multiple datasets.
- Produced insightful visualisations and key conclusions.
- Fostered strong collaboration across team roles.

Many thanks for taking the time to review this repo. 
