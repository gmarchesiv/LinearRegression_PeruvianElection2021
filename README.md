# Peruvianelections
Analysis of the results of the second round of the Peruvian presidential election 2021

Elections are facing higher scrutiny as smartphones and social media make it easier to disseminate information in real-time. The challenge for the electoral process is that greater dissemination can be, inadvertently or not, biased or not factual. Data Science can provide governments with statistical tools to improve data collection, processing, tabulating, and validation of the results. This, in turn, can provide higher transparency, expedience, and confidence in the results.

In this project, I will apply three methodologies to explore the results of the recent Peruvian presidential election. The second round took place on June 6th, 2021. One of the candidates, Keiko Fujimori has decried foul-play arising from less-than-expected results in certain regions, especially those where she did not have representatives at the polling stations. The Peruvian electoral process uses paper ballots. Ballots are discarded the same day after results are tabulated at the polling station. The poll workers submit an official handwritten ballot summary sheet to ONPE, the elections bureau. Summary sheets are signed by the three randomly assigned poll workers and a representative from each party.

The project will use like linear regression, decision tree regressor and Benford's law to highlight potential patterns arising from the data. The results of the analysis may provide recommendations for improving the transaparency of the results of the election to the public.

The project should be viewed in this sequence, with the Jupyter Notebooks coming first and Tableau last. 

# Jupyter Notebooks: 
•	Capstone – EDA : data wrangling and feature engineering to prepare data for modelling  
•	Capstone – Regression Analysis: first modelling workbook using linear regression 
•	Capstone – Decision Tree Analysis: second modelling workbook using decision tree regressor to complement findings of regression Analysis.   
•	Capstone – Benford’s Law: statistical analysis of last digit of vote count as an additional check about the fairness of the election process.  

# Tableu file: 
•	Tableau – Capstone Geoanalysis: shows patterns of outlier votes for both candidates by  State. 

# CSV files
To use with Capstone EDA
•	first_round.csv: original Spanish version of first round election results pre-EDA
•	second_round.csv: original Spanish version of second round election results pre-EDA

To use with Capstone Regression Analysis and Capstone – Decision Tree Analysis
•	merged_reg.csv: clean post-EDA file with simultaneously valid data for first and second round (also an output of running the EDA workbook)

To use with Capstone - Benford’s Law
•	first_round_clean.csv: post_EDA valid first round data (also an output of running the EDA workbook)
•	second_round_clean.csv: post_EDA valid first round data (also an output of running the EDA workbook)

To use with Tableau – Capstone Geoanalysis
•	tableaudf.csv: a file with the geocoordinates of all outliers found in the regression analysis. This file was compiled from three dataframes exported during regression analysis. The coordinates were inputted in Excel looking up a Peruvian database. In the case of observations from abroad, these were inputted manually with info from Wikipedia. Because of the considerable number of observations, it was more convenient to do in Excel  

All csv files are inside DatabasesElections.zip

# PDF file: 
Report Captsone – Giancarlo Marches.pdf: the summary of the project
