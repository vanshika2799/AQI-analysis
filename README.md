Data Description:
The dataset consists of 9358 instances, each representing hourly averaged responses from various chemical sensors. 
Ground truth hourly averaged concentrations for various pollutants including CO, Non-Metanic Hydrocarbons (NMHC), Benzene, Total Nitrogen Oxides (NOx), and Nitrogen Dioxide (NO2) were provided by a co-located reference certified analyzer. 
Missing values are tagged with -200. 

Attribute information: 
0. Date (DD/MM/YYYY)
1. Time (HH.MM.SS)
2. True hourly averaged concentration CO in mg/m^3 (reference analyzer)
3. PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
4. True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
5. True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
6. PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
7. True hourly averaged NOx concentration in ppb (reference analyzer)
8. PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
9. True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
10. PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
11. PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
12. Temperature in °C
13. Relative Humidity (%)
14. Absolute Humidity (AH)

My Work:
I've done EDA of this dataset to understand the coorelation between different features of the dataset.

Usage:
This dataset can be employed for various analyses, including:

1.Predictive Modeling: Assessing the impact of different pollutants on air quality.
2.Trend Analysis: Evaluating changes in pollutant levels over time to identify patterns or anomalies.
3.Health Impact Studies: Investigating correlations between pollutant levels and public health outcomes.

Conclusion:
The Air Quality Measurements Dataset provides critical information for understanding air quality dynamics and their implications for health and the environment. 
Researchers can utilize this dataset to develop models and insights that inform policy and public health initiatives.
