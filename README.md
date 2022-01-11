# Amazon Vine Analysis

## Overview

This analysis was created based on Amazon video game reviews. PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Once the data was loaded into pgAdmin, another analysis was done to determine if there is a bias towards favorable reviews based on Vine membership.

## Results

As you can see below, of the 18,955 useful reviews, 7,402 were 5 stars. Of this subset, 99% of reviews were given by non-members.

![image](https://user-images.githubusercontent.com/90646961/148868516-0a297fd1-2c57-4a76-803c-fab4200be5ad.png)


## Summary

Based on our results, we are unable to conclude a bias by Vine members towards higher reviews. Because 99% of 5 star reviews were given by non-members, we may be able to assume that non-members rate higher. To analize this further, an analysis similar to this should be run by all ratings and averaged. 
