# NYC-Taxi-Fare-Prediction

header_image
This notebook is using the New York Taxi Fare Dataset taken from the playground competition, hosted in partnership with Google Cloud and Coursera, tasked for predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations.

So, in this notebook we can do a lot more about the analysis especially with Geospatial Analysis along with the EDA and later we will predict the Fare price with the help of the given data using the simple Linear Regression algorithm.

Also, during time of exceution of this notebook it has been crashed multiple going out of memory due to the large amount of data from the dataset (Size: 5.7 GB, Rows[train dataset]: 55M rows) therefore the the size by taking only a random sample of 100000 rows and then only the Year having the highest traffic.

**Note: This notebook is created by getting inspired from the https://www.kaggle.com/code/breemen/nyc-taxi-fare-data-exploration?kernelSessionId=5341553 notebook
Table of Contents

Data Exploration
Feature Enginnering
2.1. Lets get a random sample of 10000
2.2. Separate the date, time and hour from the pickup time
2.3. Measure the Distance(miles) from the latitude and longitude for both pickup and dropoff
Data Cleaning
3.1. Removing the coloumns with null values
3.2. Removing the fare price less than zero
3.3. Removing the distance(mile) less than zero
3.4. Removing the key and pickup_datetime coloumn from the dataset
Data Visualisation
4.1. Visualize the geospatial locations for the pickup points
4.2. Visualize the geospatial locations for the dropoff points
4.3. Histrogram plot of fare price
4.4. Barplot for visualizing the number of rides in the following years
4.4.a. Traffic in the year 2012
4.4.b. Lets see the peaks days with their rush hours of year 2012
4.4.b1. Visualize the rush hours for monday
4.4.b2. Visualize the rush hours for tuesday
4.4.b3. Visualize the rush hours for sunday
4.4.c. Histrogram plot for the distances(mile) travelled
4.4.d. Scatter plot visualization between Fare(in $USD) vs Distance(in Miles) of year 2012
Model
5.1. Generate the test data
5.2. Train, test split of the datasets
5.3. Model Run
5.4. Model Score
5.4. Model Save
6. Conclusion
