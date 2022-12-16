# Project: Exploring eBay Car Listings on eBay Kleinanzeigen
## Introduction
In this project we work with a dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website.
To ensure the code runs quickly, on Jupyter Notebook environmentI have sampled data of 30000 data points from the full dataset. To do this we use pandas function sample() used to generate a sample random row or column from the fucntion caller dataframe.

The dfull dataset can be found at [HERE](https://data.world/data-society/used-cars-data)

The data dictionary provided with data is as follows:

- dateCrawled - When this ad was first crawled. All field-values are taken from this date.
- name - Name of the car.
- seller - Whether the seller is private or a dealer.
- offerType - The type of listing
- price - The price on the ad to sell the car.
- abtest - Whether the listing is included in an A/B test.
- vehicleType - The vehicle Type.
- yearOfRegistration - The year in which which year the car was first registered.
- gearbox - The transmission type.
- powerPS - The power of the car in PS.
- model - The car model name.
- kilometer - How many kilometers the car has driven.
- monthOfRegistration - The month in which which year the car was first registered.
- fuelType - What type of fuel the car uses.
- brand - The brand of the car.
- notRepairedDamage - If the car has a damage which is not yet repaired.
- dateCreated - The date on which the eBay listing was created.
- nrOfPictures - The number of pictures in the ad.
- postalCode - The postal code for the location of the vehicle.
- lastSeenOnline - When the crawler saw this ad last online.

The aim of this poroject is cleaning and analyzing the data included in used car listings. 

Steps:

1. Importing the libraries we need and reading the dataset into pandas.
2. Loading Dataset into our Jupyter Notebook
3. Cleaning Column Names
4. Initial Exploration and Cleaning.
5. Exploring the Odometer and Price Columns
6. Exploring the date columns
7. Dealing with Incorrect Registration Year Data
8. Exploring Price by Brand
9. Storing Aggregate Data in a DataFrame
