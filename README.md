# Impact_of_Hukou_Reform
The repository is to store all the relevant data cleaning and processing for the research project aiming to examine the impacts of China's hukou reform in 2014

Built on the data from Determinants_of_Hukou_Reform, a more refined version of scores disaggregated by policy tools is generated to be used as covariates/indicators of policy reform (please see Policy Tools as Covariates). 

Moreover, due to potential presence of multicollinearity among integration-related policy scores, a cluster dummy is adopted to replace the otherwise continuous indicators, the process of which is documented in the file "Integration Clustering".

Since the policy scores are to be weighted by city-level population size (over provincial population) and the inconsistencies of city labels (in Chinese) prevail, I went through a data cleaning process that unified the labels and merged population data of each city (342 in total) accordingly with the existing dataset. 
