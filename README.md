# Intelligent Analysis of Waste Management System in Delhi
-Self Project

## Overview
This project analyzes waste management performance across different zones in Delhi using data analysis and machine learning techniques. It combines both real-world data analysis and scenario-based simulation to understand inefficiencies and risk patterns in urban waste management.



## Objectives
- Identify high-risk zones based on waste burden and population
- Analyze waste management efficiency using simulated scenarios
- Group zones using clustering techniques
- Compare different analytical approaches for better insights



## Dataset

### 1. Real Dataset (Primary Analysis)
A dataset was created using:
- Zone-wise waste generated (TPD)
- Population (in lakh)

This dataset was used to perform:
- Waste burden analysis
- Risk classification
- Clustering of zones

### 2. Simulated Dataset (Scenario-Based Analysis)
Waste collected data was not directly available. Based on research indicating that **70–90% of total waste is typically collected in urban areas**, waste collected values were estimated to create two scenarios:
- 70% collection efficiency (low-performance scenario)
- 90% collection efficiency (high-performance scenario)

This was used to analyze the impact of efficiency on risk levels.



##  Methodology

###  Real Data Analysis (Without Waste Collected)
- Calculated *Waste per Person* = Waste Generated / Population
- Classified zones into high and low risk categories
- Applied KMeans clustering using waste generation and population

###  Scenario-Based Analysis (With Waste Collected)
- Estimated waste collected using 70% and 90% efficiency assumptions
- Calculated efficiency = Waste Collected / Waste Generated
- Performed risk classification based on efficiency
- Compared results across scenarios



## Key Results

- Zones with higher waste per person show higher environmental burden
- Population and waste generation jointly influence risk levels
- Increasing efficiency from 70% to 90% significantly reduces high-risk zones
- Clustering groups zones based on waste and population characteristics



##  Visualizations
- Waste vs Population scatter plot
- Cluster visualization of zones
- Risk distribution graphs
- Efficiency comparison (70% vs 90%)



##  Key Insights

- Waste burden per person is a strong indicator of high-risk zones
- Efficiency improvements can drastically enhance waste management outcomes
- Data-driven analysis helps identify priority zones for intervention
- Combining real and simulated data provides deeper system understanding



##  Limitations

- Waste collected data is estimated based on research assumptions
- Dataset is limited to zone-level aggregation
- Real-time and ward-level data could improve accuracy



##  Future Scope

- Predict pollution levels based on waste inefficiencies
- Use real-time data for dynamic analysis
- Apply advanced machine learning models for prediction
- Extend analysis to ward-level granularity



##  Technologies Used
- Python
- pandas
- matplotlib
- scikit-learn



## Author
Rigzin Dolkar
