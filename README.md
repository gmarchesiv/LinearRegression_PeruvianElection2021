# Peruvian election 2021 analysis
This repository contains the analysis of the results of the second round of the Peruvian presidential election 2021. 
This was my capstone project for the Data Science Bootcamp @ Brainstation. 

## Introduction
Elections are facing higher scrutiny as smartphones and social media make it easier to disseminate information in real-time through various platforms. This dissemination can be biased, intentionally or not. This poses pressures on authorities to be very transparent and clear about the results. Data Science can provide governments with statistical tools to provide higher transparency, expedience, and confidence in the results.

The second round of the Peruvian presidential elections took place on June 6th, 2021. One of the candidates, Keiko Fujimori decried foul-play because of less-than-expected results in certain regions. This electoral process used paper ballots entirely because of the Covid19 pandemic. The ballots were discarded the same day after the results were tabulated in hand-written summary sheets at the polling station. The poll workers submitted an official ballot summary sheet to ONPE, the elections bureau, for final tabulation. Summary sheets were signed by the three randomly-assigned poll workers and a representative from each party. The candidate's protests came primarily from polling stations where she did not have representatives.  

In this project, I apply three methodologies to explore the results of the election. The project uses linear regression, decision tree regressor and Benford's law to highlight potential patterns arising from the data. This analysis may provide methods for improving the presentation of the results of the election to the public.

The project should be viewed in the following sequence: 

## Jupyter Notebooks 
•	Capstone – EDA : data wrangling and feature engineering to prepare data for modelling  

•	Capstone – Regression Analysis: first modelling workbook using linear regression

•	Capstone – Decision Tree Analysis: second modelling workbook using decision tree regressor to complement findings of regression analysis   

•	Capstone – Benford’s Law: statistical analysis of last digit of vote count as an additional check about the fairness of the election process  

## Tableu file
•	Tableau – Capstone Geoanalysis: shows patterns of outlier votes for both candidates by  State. 

Jupyter notebooks and Tableau file are inside the notebook folder. 

## CSV files 
**To use with Capstone EDA**
•	first_round.csv: original Spanish version of first round election results pre-EDA

•	second_round.csv: original Spanish version of second round election results pre-EDA

**To use with Capstone Regression Analysis and Capstone – Decision Tree Analysis**

•	merged_reg.csv: clean post-EDA file with valid data for both first and second round. It is also an output of running the EDA workbook.

**To use with Capstone - Benford’s Law**

•	first_round_clean.csv: post_EDA valid first round data (also an output of running the EDA workbook)

•	second_round_clean.csv: post_EDA valid first round data (also an output of running the EDA workbook)

**To use with Tableau – Capstone Geoanalysis**
•	tableaudf.csv: a file with the geocoordinates of all outliers found in the regression analysis. This file was compiled from three dataframes exported during regression analysis. The coordinates were inputted in Excel looking up a Peruvian database. In the case of observations from abroad, these were inputted manually with info from Wikipedia. Because of the considerable number of observations, it was more convenient to do in Excel  

All csv files are inside DatabasesElections.zip

## PDF file 
Report Captsone – Giancarlo Marches.pdf: the summary of the project
