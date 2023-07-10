# Violent-Crimes-Rate
Capstone Course - Spring 2023

Purpose: Identify hierarchies of U.S. states according to violent crime rates.
Scope of Work:
  - Data Preparation: description of how the features are distributed and a statistical description of features and/or records
  - Data Analysis: Exploratory data analysis (EDA); multiple regression; agglomerative clustering
  - Data Visualization: Bar plots, scatter plots, box plots, dendrograms

As the lead and sole person working on the project, I completed all work.
All code was written in Python via Google Colab (which can be downloaded as a notebook).

### More details

The dataset utilized in the project contains statistics on arrests per 100,000 residents for assault, murder, and rape for each of the 50 US states in 1973. The numbers of arrests may not accurately reflect the actual numbers of crimes committed – particularly for rape, where it’s difficult to arrest people due to lack of evidence and DNA testing back in 1973, and rape victims may be afraid to call police after the crime was committed. The percent of population living in urban areas is also given for each state. This means that this dataset is initially very tiny – just 50 rows and five columns (State, Murder, Assault, Rape, and UrbanPop).

Conclusion: Geographic location may have a slight impact on crime rates, but it ultimately depends on HOW you're analyzing the data. If you are using the multiple regression models, then it appears that geographic locations have a stronger influence on crime rate in states, but only consistently on regional level. Additionally, there is a strong R-2 value for assault rate but it got weaker with rape and even weaker with murder. If you look at the multiple regression models at the division level (which is more granular than region), then the data is not as clear-cut. If you are using the hierarchical clusters, there are consistently three clusters with very similar V-measure scores even when playing around with the omission and level of details for the geographical location. This indicates that the geographic location had a very little impact on hierarchical clusters of states. 

