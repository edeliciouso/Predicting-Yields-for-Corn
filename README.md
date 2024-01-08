# Predicting Corn Yields For Precision Agriculture

## Group Members

- Azza Nasima	(2602158166)
- Edelyne Keisha (2602169850)
- Jessica Angela Huang (2602213031)

## Goal

To compare the machine learning models that we have chosen to predict the amount of corn that will be produced based on data from 2009 - 2019.

## Data Source

Sources for the Data :
- Crop yield : [FAOSTAT | Food and Agriculture Organization](https://www.fao.org/faostat/en/#data/QCL)
- Pesticides : [FAOSTAT | Food and Agriculture Organization](https://www.fao.org/faostat/en/#data/RP)
- Rainfall : [Our World in Data](https://ourworldindata.org/grapher/average-precipitation-per-year?tab=table)
- Fertilizer : [Our World in Data](https://ourworldindata.org/grapher/fertilizer-per-hectare?tab=table&time=latest)

## Directory

### Datasets
- faostat_corn.csv : contains the data for corn yield
- fertilizer-per-hectare : contains the uncleaned data for fertilizer
- fertilizerData : contains the cleaned data for fertilizer
- average-precipitation-per-year.csv : contains the data for rain
- faostat_pest : contains the data for pesticides

### Code
- cleaningFertilizerData.ipynb: contains the code for cleaning the fertilizer data
- MergedDataFinal4.ipynb : contains the code for merging all the data together
- DataExploration.ipynb : contains the code for data exploration (EDA)
- RandomForestCorn.ipynb : contains the testing using the Random Forest model
- LinearRegressionCorn.ipynb : contains the testing using the Linear Regression model
- DecisionTreeCorn.ipynb : contains the testing using the Decision Tree model
- RidgeRegressionCorn.ipynb : contains the testing using the Ridge Regression model
- XGBoostCorn.ipynb : contains the testing using the XGBoost model
- KNNCorn.ipynb : contains the testing using the K-Nearest-Neighbors model
