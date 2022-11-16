# am10_group_project

## Proposal

### Context & Dataset

Our topic is crime in San Francisco over time. Our dataset came from <https://www.kaggle.com/datasets/kaggle/san-francisco-crime-classification>. This dataset covers 12 years (2003 - 2015) of crime data in San Fransisco, with variables including time (date, day of week), location (address, police department district, longitude and latitude), and crime facts (crime category, description, resolution). In addition to this base dataset, we plan to add more overarching variables involving public health, wealth and safety to understand any relation with crime rates.

### Project Goals

**Visualisation**

We plan to use data visualisation techniques in R to explore relationships of criminal incidents with time and location. Visualisation ideas include: 

(1) Location and crime category

(2) Number of arrests in specific police department districts

(3) Crime rates across time frames for different categories

**Modelling**

Our statistical models include OLS and logistical regressions, using machine-learning techniques. We plan to firstly model crime category against time and location variables using OLS regression on the training set to predict crime categories in the testing set. We then may turn arrest into a binary variable and model probability of arrest using logistical regression against some variables of interest.

### Further information
We will also incorporate additional macroeconomic explanatory variables of crime incidences, including indicators such as unemployment and inflation rates over time, to identify factors causing fluctuations in crime rates, changes in crime categories etc over time.
