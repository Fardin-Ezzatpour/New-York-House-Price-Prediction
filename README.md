# New York House Price Prediction

## Introduction

This project is a machine learning model designed to predict house prices in New York City. It uses data related to home sales in New York and employs various machine learning algorithms to achieve accurate price predictions.

## Dataset Features

The dataset includes the following information:

*   `BROKERTITLE`: Broker Title
*   `TYPE`: Type of property (Condo, House, etc.)
*   `PRICE`: Property Price
*   `BEDS`: Number of Bedrooms
*   `BATH`: Number of Bathrooms
*   `PROPERTYSQFT`: Property Square Footage
*   `ADDRESS`: Property Address
*   `STATE`: State
*   `MAIN_ADDRESS`: Full Address
*   `ADMINISTRATIVE_AREA_LEVEL_2`: Administrative Area Level 2
*   `LOCALITY`: Locality
*   `SUBLOCALITY`: Sublocality
*   `STREET_NAME`: Street Name
*   `LONG_NAME`: Long Name
*   `FORMATTED_ADDRESS`: Formatted Address
*   `LATITUDE`: Latitude
*   `LONGITUDE`: Longitude

## Required Libraries

To run this project, you need to install the following libraries:

*   `pandas`: For data manipulation and analysis
*   `matplotlib`: For data visualization
*   `seaborn`: For data visualization
*   `numpy`: For numerical computations
*   `scikit-learn` (sklearn): For machine learning algorithms and data preprocessing
*   `xgboost`: For XGBoost model
*   `plotly`: For interactive data visualization
*   `bidi-algorithm`: For supporting right-to-left texts (like Persian/Farsi)
*   `python-bidi`: For supporting right-to-left texts (like Persian/Farsi)
*   `reportlab`: For generating PDF files with Persian/Farsi text support

```bash
pip install pandas matplotlib seaborn numpy scikit-learn xgboost plotly bidi-algorithm python-bidi reportlab
