# MACHINE LEARNING CO2 PROJECT
This project is based on an analysis of carbon dioxide (CO2) emissions linked to the agri-food industry, which plays a crucial role by contributing 62% of global CO2 emissions. The primary objective lies in anticipating future CO2 emissions and determining whether or not it influences climate change. To achieve this purpose, it focuses on two fundamental variables: the total CO2 emissions, represented by the label 'total_emission', and the average temperature, represented by the label, 'Average Temperature °C'.

The adoption of these variables seeks to generate a more in-depth and effective understanding of the dynamics of emissions in the agri-food field and its relationship with climate changes. The aim is to identify patterns and relationships between emissions and thermal variations. Based on these findings, we aim to propose and discover potential mitigation pathways, outlining concrete actions that can contribute to effectively addressing this environmental problem.

The methodology involves advanced statistical analysis and predictive modeling techniques, taking advantage of Machine Learning tools to anticipate future CO2 emissions scenarios. This analysis is shown to be an important instrument to estimate the effects of increased emissions on the global climate system and guide informed decision-making.

This project seeks to understand and project CO2 emissions in the agri-food industry, while seeking to provide decision makers with greater tools with crucial information to address critical environmental challenges and promote practices that aim for a sustainable future.

## Business Context
Over the years, CO2 emissions have experienced a constant increase, while the average temperature on each continent has followed an upward trend. This upward dynamic has been maintained over time.

There are records from 1990 to 2020 in each of the variables that make up the data set.

We wish to estimate the future effects of emissions in order to make decisions regarding prevention and how the effects of CO2 can be reduced and thus better address current environmental challenges such as climate change.

## Analytical Context:
There is a data set in a CSV file called "Agrofood_co2_emission.csv" that is stored in the "Databases" folder in Drive.

The data set has variables of interest such as:

Total Population - Female
Total Population - Male
total_emission
Average Temperature °C
Implemetaré las siguientes tareas con los datos:

**1- Transformation and preparation of data for visualizations.**

**2- Cleaning the Dataset.**

**3- Creation of visualizations to obtain insights and answer problem questions.**

The questions to answer are the following:

- *What has been the behavior of the average temperature over the years?*

- *Have CO2 emissions increased, decreased or remained stable in recent years?*

- *Which continent has contributed the most CO2 emissions over the years?*

- *What has been the temperature variation on each continent over the years?*

- *Is there a correlation between average temperature and CO2 emissions?*

- *Does the average temperature have many atypical values?*

**4- Creation of new variables and dimensionality reduction using the PCA technique.**

**5- Parameter optimization using GridSearchCV.**

**6- Training the Dataset with the following algorithms.**

- Random Forest Regressor
- GradientBoosting
- AdaBoost
- XGB Regressor
