# INSAID2021-ML-Intermediate-Avocado_Price_Prediction
INSAID 2021 ML Intermediate Term Project
# Project Description
## Introduction
Client for this project is a major Avocado Producer.

Their avocados are sourced from over 1000 growers owning over 65,000 acres across California, Mexico, Chile, and Peru.
With generations of experience growing, packing, and shipping avocados, they have a deep understanding of the avocado industry.

Their aim is to source quality fruit that’s sustainably grown and handled in the most efficient, shortest supply route possible.
They want to increase their supply throughout the United States and need to make sure that they are selling their products at the best possible price.

## Current Scenario
Avocado prices have rocketed in recent years by up to 129%, with the average national price in the US of a single Hass avocado reaching $2.10 in 2019, almost doubling in just one year.

Due to this uncertainty in the prices, the company is not able to sell their produce at the optimal price.

## Problem Statement
The current process suffers from the following problems:

* The price of avocado is dependent on global demands and seasonal production.
* Due to these reasons, it is quite difficult to know for certain the price in the future.

They want to automate the process of predicting the future price of avocado, based on the historical data.

## Project Task
* Dataset containing the weekly retail scan data of avocadoes is provided.
* Project task is to build a regression model using the dataset.
## Project Deliverables
* Deliverable: Predict the average price of a single avocado.
* Machine Learning Task: Regression
* Target Variable: AveragePrice
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the RMSE score.
# Data Description
* The dataset contains weekly retail scan data for National Retail Volume (units) and price.
* Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados.
* The column AveragePrice is the average price of a single avocado.

This is the data that we have to predict for future samples.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 14599 rows and 14 columns.
* The last column AveragePrice is the target variable.

## Test Set:
* The test set contains 3650 rows and 13 columns.
* The test set doesn’t contain the AveragePrice column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique identity of each observation                          |
|02| **Date** | The date of the observation                 |
|03| **AveragePrice**        | The average price of a single avocado            |
|04| **TotalVolume**          | Total number of avocados sold                     |
|05| **4046**      | Total number of avocados with PLU 4046 sold                  |
|06| **4225**           | Total number of avocados with PLU 4225 sold
|07| **4770**     | Total number of avocados with PLU 4770 sold |
|08| **TotalBags**     | Total number of bags sold|
|09| **SmallBags**        | Total number of small bags sold|
|10| **LargeBags**          | Total number of large bags sold  |
|11| **XLargeBags**         | Total number of extra-large bags sold |
|12| **type**     | Type of an avocado (conventional or organic)  |
|13| **year**     | 	The year of observation  |
|14| **Region**     | The city or region of the observation |
