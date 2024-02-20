# *NYC Ticket-Violation*

## Description
Identifying missing values

## :relaxed: Overview and Objectives

In this exercise, we’re going to identify missing values, one of the most common problems that you will encounter. We’ll see just how often there are missing values, and what effect they might have. 
We are only interested in a handful of the columns:

Plate ID
Registration State
Vehicle Make
Vehicle Color
Violation Time
Street Name

Questions

1. How many rows are in the data frame when it is read into memory?
2. Remove rows with any missing data (i.e., a NaN value). 
3. How many rows remain after doing this pruning? 
4. If each parking ticket brings $100 into the city, and missing data means that the ticket can be successfully contested, how much money might New York City lose as a result of such missing data?
5. Let’s instead assume that a ticket can only be dismissed if the license plate, state, car, make, and/or street name are missing. Remove rows that are missing one or more of these. How many rows remain?
6. Assuming $100/ticket, how much money would the city lose as a result of this missing data?

## :computer: Setup
Install the following libraries to be able to run the jupyter notebook
* *pip install pandas*
* *pip intall matplotlib*
* *pip install seaborn*

Create a data frame from the file __nyc-parking-violations-2020.csv__ 

## :scroll: Author
Gloria Givondo

## License
The content of this site is license under the MIT license
Copyright (c) 2024 **Gloria**