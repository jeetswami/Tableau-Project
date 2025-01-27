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

  ![Total attacks over time.png](https://github.com/jeetswami/Tableau-Project/blob/85c51722d037e2691bdb42de8f61b9edb53cbe96/Total%20attacks%20over%20time.png)

  - Regional Analysis: A bar graph highlighting the Middle East and North Africa as the most affected regions, with Australasia and Oceania being least impacted.
  
  ![Regional Analysis](https://github.com/jeetswami/Tableau-Project/blob/d8d6b55d53d2385c1ce183a9d87e7594770091eb/Regional%20Analysis.png)

  - Terrorism Success Rates: Regional differences in the effectiveness of terrorist strikes, with a focus on Middle East and South Asia.

  ![Terrorism Success Rates](https://github.com/jeetswami/Tableau-Project/blob/d8d6b55d53d2385c1ce183a9d87e7594770091eb/Terrorism%20Success%20Rate.png)

  - Total Deaths by Country: A bubble chart representing the human cost of terrorism, with Iraq and Afghanistan bearing the highest death tolls.

  ![Total Deaths by Country](https://github.com/jeetswami/Tableau-Project/blob/d8d6b55d53d2385c1ce183a9d87e7594770091eb/Total%20Death%20per%20country.png)

  - Active Terrorist Groups: Insights into the most lethal groups, such as the Taliban and ISIL.

  ![Active Terrorist Groups](https://github.com/jeetswami/Tableau-Project/blob/d8d6b55d53d2385c1ce183a9d87e7594770091eb/Most%20Active%20Terrorist%20Organizations.png)

  - Attack Types: Analysis of methods, with "Bombing/Explosion" being the most common.

  ![Attack Types](https://github.com/jeetswami/Tableau-Project/blob/d8d6b55d53d2385c1ce183a9d87e7594770091eb/Method%20of%20Attack.png)

3) Analysis:
   
<p align="justify">
The analysis of global terrorism trends from 1970 to 2017 revealed significant insights. A sharp increase in terrorist activities was observed after 2006, peaking in 2014. The Middle East and North Africa emerged as the most affected regions, while Australasia and Oceania experienced the fewest attacks. Iraq was identified as the most impacted country, with 24,636 attacks and a death toll of 78,589, followed by Afghanistan. Bombing and explosions were the most commonly employed attack methods, with armed assaults following closely. Among terrorist groups, the Taliban and ISIL caused the most casualties. These findings underscore the importance of understanding regional and temporal patterns to inform and develop targeted security strategies.
</p>

4) Dashboard:

![](https://github.com/jeetswami/Tableau-Project/blob/eb279c6596440ecd0c025b9952d389388eec179c/Dashboard.png)
