# Amazon_Vine_Analysis

## Overview
For this project, I analyzed Amazon Reviews written by members of the paid Amazon Vine Program. The dataset I chose to look at contained reviews on Furniture. I took the following steps to complete this project: 1. Created an AWS RDS database 2. Used PySpark to extract and transform the data into Colaboratory 3. Loaded the data into pgAdmin 4. Used PySpark to determine results and potential bias toward favorable reviews   

## Results

- Create a DataFrame where there are 20 or more total votes

<img width="1907" alt="20 or more total votes" src="https://user-images.githubusercontent.com/111243284/208478208-db7a8b5e-4215-4d36-9930-2b06671aa6e6.png">


- Data is filtered where percentage of helpful votes is greater than or equal to 50%

<img width="1884" alt="helpful votes is greater than 50%" src="https://user-images.githubusercontent.com/111243284/208478375-ec5e3cff-4fe1-447a-aefd-deab3317d8b2.png">


- How many Vine Reviews were there?

<img width="335" alt="total paid reviews" src="https://user-images.githubusercontent.com/111243284/208480207-9f55058d-c7cc-446b-af7b-403e13c8b80d.png">


- How many Non-Vine Reviews were there?

<img width="361" alt="unpaid vine reviews" src="https://user-images.githubusercontent.com/111243284/208480237-e8a444d7-6d69-470b-ad77-8e1dffe5b944.png">


- How many Vine reviews were 5 stars?

<img width="631" alt="5 star paid reviews" src="https://user-images.githubusercontent.com/111243284/208479639-f12fd704-f727-49c1-9658-5ccfeac9c597.png">


- How many Non-Vine reviews were 5 stars?

<img width="680" alt="5 star unpaid reviews" src="https://user-images.githubusercontent.com/111243284/208479621-bf3efb30-a5a9-451b-877a-ed69b0caab73.png">


- What percentage of Vine Reviews were 5 stars?

<img width="655" alt="percentage of 5 star reviews for vine" src="https://user-images.githubusercontent.com/111243284/208479260-0afc3a29-55f0-478d-833a-fa2d48859fbe.png">


- What percentage of Non-Vine Reviews were 5 stars?

<img width="706" alt="percentage of 5 star reviews for unpaid vine" src="https://user-images.githubusercontent.com/111243284/208479208-2668922a-53a3-4ce7-98a1-18f99564c9c8.png">


## Summary



