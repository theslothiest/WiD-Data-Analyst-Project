# WiD-Data-Analyst-Project
A Python beginner's portfolio project for Women in Data's Data Analyst Program.

Focus on job satisfaction and how the chosen variables (age, compensation, country/region/continent, education level/college attendance, employment level, ethnicity, gender, sexuality, weekly work hours, professional years of experience) possibly impact it.


Notes: Before starting regressions and analysis, best to create a correlation matrix for the chosen variables, so as to drop any variables with too low or too high of a correlation. The model(s) are highly likely to end up with strong multicollinearity due to the excessive categorical variables.


Data was pulled from Stack Overflow Annual Developer Survey, 2020 results specifically. Most of the cleaning (i.e. removal of unnecessary variables, missing entries, etc.) was performed in Excel before exporting to Google Colab. Cleaned Excel data file along with csv file has been uploaded. Raw data can be found through the link below.

Link to the raw data: https://insights.stackoverflow.com/survey


Code references:
https://stackoverflow.com/questions/50733014/linear-regression-with-dummy-categorical-variables
https://stackoverflow.com/questions/34007308/linear-regression-analysis-with-string-categorical-features-variables


A guide to interpret results:
https://medium.com/swlh/interpreting-linear-regression-through-statsmodels-summary-4796d359035a
