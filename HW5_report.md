# Homework 4: 
**Name:** Aamr Ibrahim  
**HW Number:** HW4 

**Class:** CS 625 - Data Visualization  
**Due Date:** March 16, 2025

# Selected DataSet: Dataset 13
13 - State Population--Rank, Percent Change, And Population Density

# Introduction
 Using help of various kinds of data visualization, this report uses U.S. state population density from  1960 to 2009. It will be very helpful to understand reasons for population distributions and interpret the results using boxplot , scatterplot and eCDF.

# Data Prepocessing
 Before visualizing, cleaning and sorting of the dataset was done. The preprocessing steps included:
 * Loading  the dataset: The CSV file was imported using Pandas.

 * Cleaning data: Removing metadata rows, and  redundant column names. Renaming columns to make them consistent Numerical columns were converted to the right  data type.
* Dropping metadata rows and redundant headers.
* Renaming columns for consistency.Converting numerical columns to the correct data type.
* Sorting and structuring: The file was sorted by state name to maintain file coherency.

# Part 1: Distribution Charts

## Chart 1: Boxplot 
Title: Population Desnity
Description: 
* In the bloxplot using the colab below represents the distrubution of population density for state years 1980 , 1990 , 2000 and 2009. For each year they have their own IQR using each box for each state with indiviual by points.


First Chart
[Go to "FIrst chart(Boxplot)" header to find the first chart](https://colab.research.google.com/drive/17AfgRxUys83maR09Go9oEZcE5RyK7Vxs#scrollTo=1IRpWuDCDcgI)

## Advantages and Disadvantages for the First chart:
Advantages:
* The boxplot chart effectively displays the median, spread, and outliers, it does so in a straightforward manner allowing for simple interpretation.

Disadvantages:

* Determining precise density values proves difficult as reading the plot requires some estimation rather than permitting outright recognition of numbers.

Observations:

* The observations from the boxplot chart indicate that population density fails to remain constant over time instead demonstrating an incline. Moreover, some extreme outliers likely represent heavily populated states similar to New York with its bustling city or California with various metropolitan areas experiencing substantial increases.

### Chart 2: Histogram
Title: Population Density (1960)

Description

* In the histogram using the colab below has a representation of the state-wide population density distribution in 1960.

[Go to "Second Chart(Histogram):" header to find the Second chart](https://colab.research.google.com/drive/17AfgRxUys83maR09Go9oEZcE5RyK7Vxs#scrollTo=1IRpWuDCDcgI)

## Advantages & Disadvantages for the Second chart:

Advantages: 
* The frequency of different ranges of population densities is shown effectively.

Disadvantages: 
* The bin sizes may affect the interpretation. The results may be misleading due to the presence of skewness. 

Observations

* Most of the states had low population densities in 1960.

* A few states had some very high density values, producing a right-skewed distribution.


### Chart 3: eCDF
Title:  Population Density (1960 vs 2009)
Description:
In the eCDF using the colab below compares population density distributions from 1960 and 2009.

[Go to "Third Dataset(eCDF):" header to find the Third chart](https://colab.research.google.com/drive/17AfgRxUys83maR09Go9oEZcE5RyK7Vxs#scrollTo=1IRpWuDCDcgI)


# Advantages & Disadvantages for the Third chart:

 Advantages:
 * This information builds up every year, so it is possible to compare different periods easily.

 Disadvantages:
* It might seem a bit counterintuitive to some people when you compare it to histograms.

# Observations:
* The way population density was spread out changed a lot from 1960 to 2009.
*  The number of states with lower population densities is reduced which indicates that overall rate of urbanization is  increasing.

# Part 2: Further Analysis and Findings 

## Finding 1: Trend in Urbanization

* eCDF comparison revealed an increase in the population density levels that is consistent with the process of urbanization.

* Use of scatter plots also confirmed that states with low historical densities experienced significant growth.

## Finding 2: Outlier States

* Boxplots showed that there were a few states that have always had very high densities.

* When these outliers were investigated, it was observed that some states like New Jersey and Rhode Island have always been densely populated while many of the Midwestern states have remained relatively sparse.













