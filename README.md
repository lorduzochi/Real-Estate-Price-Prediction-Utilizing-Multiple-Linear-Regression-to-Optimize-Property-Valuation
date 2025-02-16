# Real Estate Price Prediction Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Aim of the Project](#aim-of-the-project)
- [Data Description](#data-description)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Key Learning Points](#key-learning-points)
- [Data Analysis](#data-analysis)

## Project Overview

This project involved an in-depth exploration of property valuation optimization through the use of Multiple Linear Regression in Microsoft Excel, aimed at refining accuracy in property values. The project addressed market volatility and localized influences by leveraging data-driven insights and advanced analytical techniques. My role was critical in enhancing RealEstateBud’s capability to deliver precise and transparent property valuations, thereby fortifying its competitiveness and instilling trust among clients.


![Regression Statistic](https://github.com/user-attachments/assets/f7060cb7-fa39-461e-853e-5887b916c446)

## Business Problem

Manila experiences rapid shifts in property values due to factors such as urban development projects, changes in local ordinances, and shifts in buyer preferences. Staying abreast of these trends, and accurately predicting their impact on property values is a complex endeavor.

## Rationale for the Project

Multiple Linear Regression is a statistical method that enables the modeling of complex relationships between multiple factors and a single outcome variable. In the real estate domain, it allows for the consideration of numerous variables, such as property features and location, to provide a comprehensive approach to property valuation.

## Aim of the Project

The project focuses on utilizing a data-driven approach to property valuation at RealEstateBud in Manila. The primary goal is to create a robust valuation model utilizing Multiple Linear Regression, incorporating a number of factors. This model aims to significantly enhance the accuracy and transparency of property valuations, bridging the gap between estimated and actual property values.

## Data Description

- Price: The listed price of the property.
- Bed: The number of bedrooms in the house.
- Bath: The number of bathrooms in the house.
- Acre_Lot: The size of the lot in acres.
- House_Size: The total size of the house in square feet.
- Garage: The number of parking spaces in the garage.
- Swimming_Pool: Indicates whether the property has a swimming pool (1 for yes, 0 for no).
- House_Age: The age of the house in years.
- Safety_Index: A safety index score associated with the property location.


## Data Source

real_estate_price: The primary dataset used for this analysis is the "real_estate_price.csv" file, containing detailed information about each property valuation.

## Tool

- Microsoft Excel - used for Descriptive, Diagnostics and Predictive Analytics.

## Data Cleaning and Preparation

At the initial data preparation phase, we performed the following task;

1. Data loading and inspection
2. Data cleaning anf formatting


## Key Learning Points

- Exploratory Data Analysis
-	Feature Engineering
-	Multiple Linear Regression
-	Model Development
-	Model Evaluation
-	Data Visualization

![Descriptive Statistic](https://github.com/user-attachments/assets/93c69061-1966-4874-b330-528e5a1916ca)


## Data Analysis

~~~
Price Prediction Formula = 199968.139619402 + (12544.6085385179 * Bed)
+ (3125.03547642441*Bath) + (59733.9777339705*Acre_Lot)
+ (72.41262996283220233.5441523275*Garage) + (17976.2887002955*Swimming_Pool)
+ (-3962.17842795843*House_Age) + (1025.72743770586*Safety_Index))
~~~

![Price Prediction calculator](https://github.com/user-attachments/assets/9e620555-d5ce-4391-a5d4-7517b42771c0)
