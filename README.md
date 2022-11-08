# am10_group_project

## Proposal

Our topic is crime. Our dataset came from <https://www.kaggle.com/datasets/kaggle/san-francisco-crime-classification>. This dataset covers 12 years (2003 - 2015) of crime data in San Fransisco, with variables including time (date, day of week), location (address, police department district, longitude and latitude), and crime facts (crime category, description, resolution). 

We plan to use visualisation to explore relationships crime has with time and location. Visualisation ideas include location and crime category, number of arrests in specific police department districts etc. 

Our statistical models include OLS and logistical regressions, using machine-learning techniques. We plan to firstly model crime category against time and location variables using OLS regression on the training set to predict crime categories in the testing set. We then may turn arrest into a binary variable and model probability of arrest using logistical regression against some variables of interest.

If needed, we will also incorporate additional macroeconomic explanatory variables of crime incidences, including indicators such as unemployment and inflation rates over time, to identify factors causing fluctuations in crime rates, changes in crime categories etc over time. 
