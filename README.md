# Advanced Regression

Advanced Regression by Nishadh Shrestha

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

## Conclusions

We aim to answer the following question by creating a linear regression model from the dataset.

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

According to the final model we have choosen these questions can be answered as following:

In conclusion, the top 10 most features (ordered by importance) that help predict the house price include the following.

1. **TotalArea**: Total internal area of the house **highly positively correlated** with price
2. **OverallQual**: Overall quality of the house (**higher the better price**)
3. **OverallCond**: Overall condition of the house (**higher the better price**)
4. **PropertyAge**: Property age at time of sale (**younger the better price**)
5. **MSZoning_FV**: Floating Village Residential draws **higher price**
6. **Exterior1st_BrkComm**: Houses with common brick exterior covering draws **lower price**
7. **TotalBath**: Total number of bathrooms (**more the better price**)
8. **SaleCondition_Partial**: This is associated New Homes and it draws **higher price**
9. **YearBuilt_1927**: Houses built in 1927 draws **lower price**
10. **MSZoning_RL**: Residential Low Density zoning draws **higher price**

## Technologies Used

- numpy 1.24.3
- pandas 1.5.3
- seaborn 0.12.2

## Acknowledgements

- Learning from Advanced Regression course by [Anjali Rajvanshi](https://in.linkedin.com/in/anjalirajvanshi)
- Learning from Model Selection course by [Prof. G. Srinivasaraghavan](http://iiitb.ac.in/faculty_page.php?name=GSrinivasaraghavan)
- Guidance from live session by [Akashdeep Makkar](https://www.linkedin.com/in/akashdeep-makkar-12110880/)

## Contact

Created by [@nishadh] - feel free to contact me!
