# Crowdfunding-ETL

## Overview

The purpose of this analysis is to provide a company information about the backers who've pledge to live projects from a new dataset they just received. To accomplish this task, we want to perform both an ETL process on this data set as well as using SQL queries.

The steps we are going to take are the following:

- We will Extract the data.
- Transform and clean the data.
- Create an ERD and Table Schema.

## Extract the Data.

The first step is to extract the data so it can go from this:
	
![extract1](https://user-images.githubusercontent.com/118491043/233881612-3f834ca9-5717-4595-b1b9-09520ca43c81.png)

To this:

![extract2](https://user-images.githubusercontent.com/118491043/233881630-25fa4105-a23d-46ad-93d8-7016b5b77384.png)

## Transform and Clean the Data

This step is self explanatory, we just have to make sure the data is presentable and is easy to read.

![clean_data](https://user-images.githubusercontent.com/118491043/233882248-aaf70f52-b163-4e4f-bb33-ec3a13f59ed1.png)

## ERD & Table Schema

![crowdfunding_db_relationships](https://user-images.githubusercontent.com/118491043/233882331-38aa786d-d049-4958-8986-a5c71ff3213a.png)

This is how I created a visual of the connections between the data before importing it into SQL. By doing this it was a lot easier to create the tables in SQL to get the information for the backers. 

