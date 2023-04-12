# Bike Sharing Demand Prediction

Bike sharing system is an innovative transportation strategy that provides individuals with bikes for their common use on a short-term basis for a price or for free. Over the last few decades, there has been a significant increase in the popularity of bike-sharing systems all over the world. This is because it is an environmentally sustainable, convenient and economical way of improving urban mobility. In addition to this, this system also helps to promote healthier habits among its users and reduce fuel consumption.

# Problem statement:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Dataset description:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

# Attribute Information:

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Project Flow:

1. Initial preparations(Loading the dependencies and the data)

2. EDA

3. Clean-Up

Handling null values

Handling duplicate values

Removing Outliers

Feature engineering

4. Feature encoding

Checking correlation for feature removal

Removing Multicollinearity

Obtaining correlation between dependent and independent variables

Pre processing of the data

5. Target feature conditioning

Creating train and test dataset

Feature Scaling

6. Model implementation

Linear Regression

Ridge Regression

Lasso Regression

Random forest regression

XGBoost

7. Model explainability

# Conclusion:

EDA insights:

1. Most number of bikes are rented in the Summer season and the lowest in the winter season.
2. Over 96% of the bikes are rented on days that are considered as No Holiday.
3. Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.
4. Most number of bikes are rented when there is no snowfall or rainfall.
5. Majority of the bikes are rented for a humidity percentage range of 30 to 70.
6. The highest number of bike rentals have been done in the 18th hour, i.e 6pm, and lowest in the 4th hour, i.e 4am.
7. Most of the bike rentals have been made when there is high visibility.

Challenges faced:

1. Removing Outliers.
2. Encoding the categorical columns.
3. Removing Multicollinearity from the dataset.
4. Choosing Model explainability technique.
