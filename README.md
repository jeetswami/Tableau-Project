# Tableau-Project

# 1. Introduction

## Domain and Problem Description
The project focuses on analyzing the Global Terrorism Database (GTD) to derive insights into terrorist activities worldwide. Key objectives include studying the frequency and trends of attacks over time, identifying regions with divergent trends, uncovering correlations between incidents and casualties, and assessing attack tactics. This analysis aims to support security strategies and policy formulation.

### Tools Used: R and Tableau
### Data Source: Global Terrorism Database (1970–2017), managed by START at the University of Maryland.
### Key Features: Over 180,000 incidents, 100+ variables, and a rich dataset enabling in-depth analysis.

# Data Workflow

1) Data Cleaning, Processing and EDA:
  - Handling Missing Values: Replaced NaN/missing values with placeholders like 'UNKNOWN' for categorical variables and mode/zero for numerical variables.
  - Data Transformation: Renamed columns, converted data types, and categorized values for clarity and usability.
  - Country Standardization: Used a package to ensure consistency in country names.
  - Final Dataset: Reduced from 181,619 rows and 135 columns to 181,513 rows and 26 variables after cleaning. Key variables included year, location, attack type, casualties, and terrorist groups.

2) Data Visualization:
  - Total Attacks Over Time: A time-series graph showcasing a spike in terrorist activities post-2006, peaking in 2014.

  [Total Attacks Over Time] ![Total attacks over time.png]
