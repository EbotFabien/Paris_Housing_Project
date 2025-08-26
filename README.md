# 🏠 Paris Housing Price Prediction
This project explores real estate prices in Paris and builds machine learning models to predict house/apartment values based on features such as:

* 📏 Size (square meters)

* 🛏️ Number of rooms

* 📍 Location (postal codes/arrondissements)

* 🏢 Property type (apartment or house)

* 📅 Year built and amenities

* 🔍 Project Goals

Perform Exploratory Data Analysis (EDA) to uncover price trends in Paris.

Build regression models (Linear Regression, Random Forest, XGBoost) to predict property prices.

Evaluate models using metrics such as RMSE, MAE, and R².

Visualize results with maps and charts to understand spatial and economic factors affecting real estate in Paris.


# Dataset Description
The dataset used in this project consists of synthetic data on house prices in Paris. It includes numeric attributes representing various features of the properties. This dataset is particularly valuable for educational purposes, practice, and gaining knowledge in machine learning and data analysis.

The dataset can be found on Kaggle: [Paris Housing Price Prediction](https://www.kaggle.com/datasets/mssmartypants/paris-housing-price-prediction).

# Context and Content do Dataset
This dataset is created from synthetic data representing house prices in the urban environment of Paris. It is ideal for educational purposes, practice, and gaining essential knowledge in machine learning and data analysis.

Next, the goal is to create a classification dataset from the existing data by adding a new column for the class attribute.

The dataset contains more than just rows and columns, it includes detailed house attributes listed as column names.

# Description of Dataset Columns
All attributes are numeric variables and are listed below:

* squareMeters: Total area of the house in square meters.

* numberOfRooms: Total number of rooms in the house.

* hasYard: Indicates whether the house has a yard (1 for yes, 0 for no).

* hasPool: Indicates whether the house has a pool (1 for yes, 0 for no).

* floors: Number of floors in the house.

* cityCode: Zip code of the house's location.

* cityPartRange: A range value indicating the exclusivity of the neighborhood; higher values denote more exclusive areas.

* numPrevOwners: Number of previous owners the house has had.

* made: Year the house was built.

* isNewBuilt: Indicates whether the house is newly built (1 for yes, 0 for no).

* hasStormProtector: Indicates whether the house has storm protection features (1 for yes, 0 for no).

* basement: Area of the basement in square meters.

* attic: Area of the attic in square meters.

* garage: Size of the garage in square meters.

* hasStorageRoom: Indicates whether the house has a storage room (1 for yes, 0 for no).

* hasGuestRoom: Number of guest rooms in the house.

* price: Predicted price value of the house.
