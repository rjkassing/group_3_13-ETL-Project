Project Report
Extract: We started with datasets about World Happiness and Access to Water that were available as csv files from Kaggle and Gapminder. We selected these because they contained annual reports organized be country.
Transform: In Jupyter Notebook, we used Pandas to transform the csv files into dataframes. We performed a left merge (prioritizing World Happiness) and removed any duplicate countries and null data. In this process, we found that the World Happiness dataset had less countries reporting data than the Access to Water dataset. And we cleaned Country names based on latest political alignments for merging.

Load:
We chose this final dataset to perform the following potential analysis:
Correlation between happiness and access to water (hypothesis 1:1 ratio)
Group by Region for correlation analysis
Pull in additional years of happiness data to understand trends