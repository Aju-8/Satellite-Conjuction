# Conjunctions in Space Data Analysis and Visualization
## Overview
This repository contains data analysis and visualization work focused on conjunctions in space, where Resident Space Objects (RSOs) in Earth's orbit may pass dangerously close to each other. The goal of this project is to explore patterns, correlations, and distributions within the dataset, providing valuable insights for understanding and managing conjunction scenarios.

## Data Analysis Process
### Dataset Description:

The dataset includes key fields such as NORAD Catalog IDs, object names, days since epoch, time of closest approach (TCA), TCA range, TCA relative speed, maximum probability (MAX_PROB), dilution threshold (DILUTION), and status information.
### Data Cleaning:

Initial steps involved cleaning the dataset, handling missing values, and ensuring data consistency.
### Exploratory Data Analysis (EDA):

Utilized Python for exploratory data analysis to gain insights into the distribution of satellite statuses, temporal patterns, correlations between numerical fields, and the presence of outliers.
### Tableau Dashboard Creation
### Overview Dashboard:

Created an overview dashboard displaying key summary statistics and a bar chart showcasing the count of conjunctions by satellite status For both the satellite which are Object_Name_1 & Object_Name_2

Provided the Link Below for your reference.

### First Satellite Overview :
https://public.tableau.com/app/profile/ajith2468/viz/Satellite_16997095211690/FirstSatellite?publish=yes

### Second Satellite Overview :
https://public.tableau.com/app/profile/ajith2468/viz/Satellite_16997095211690/SecondSatellite?publish=yes

## Conclussion:

In conclusion, the analysis of conjunctions in space has provided a multifaceted understanding of the dynamics surrounding Resident Space Objects (RSOs) in Earth's orbit. Through a meticulous data exploration process and the creation of interactive Tableau dashboards, valuable insights have been gleaned, contributing to the enhancement of space situational awareness. Here are key takeaways from the assessment:

### Temporal Patterns and Seasonality:
The temporal analysis revealed discernible patterns and fluctuations in conjunction occurrences over time. Peaks and troughs in the daily distribution suggest potential seasonality or periodic trends, crucial for anticipating variations in conjunction scenarios.

### Correlation Insights:
The correlation overview dashboard highlighted relationships between key numerical fields. Notably, moderate positive correlations were identified between 'TCA_RELATIVE_SPEED' and 'DILUTION', as well as a stronger positive correlation between 'TCA_RANGE' and 'DILUTION'. These insights are instrumental in understanding the interplay of variables in conjunction scenarios.

### Risk Assessment and Outlier Detection:
The risk assessment dashboard provided a visual assessment of the relationship between 'TCA_RANGE' and 'TCA_RELATIVE_SPEED', helping identify potential high-risk conjunctions. Additionally, the outlier detection dashboard equipped analysts with tools to pinpoint extreme values and assess their impact on conjunction scenarios.

### Status and Satellite-Specific Analysis:
The satellite status comparison dashboard illustrated the distribution of conjunctions based on different statuses, providing valuable information for satellite operators. The satellite-specific dashboard allowed for a detailed exploration of specific satellite data, facilitating a more granular understanding of conjunction scenarios.

### Distribution Characteristics:
The distribution analysis dashboards shed light on the characteristics of 'TCA_RANGE' and 'TCA_RELATIVE_SPEED', offering insights into their central tendencies, spread, and the presence of outliers. Understanding these distributions is essential for making informed decisions regarding the variability and risk associated with conjunctions.

### Interactive Data Exploration:
The interactive Tableau dashboards empower users to dynamically explore the data, filter information based on specific criteria, and gain insights tailored to their needs. This user-friendly interface enhances the utility of the analysis for a wide range of stakeholders.

This comprehensive analysis and visualization endeavor contribute to the broader objective of enhancing space safety and operational efficiency. The insights generated from this assessment provide a foundation for continued research, risk mitigation strategies, and informed decision-making in the realm of space situational awareness.


