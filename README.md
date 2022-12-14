# Phase 2 Project
## Predicting House Sale Prices in King County

![awesome](images\brian-babb-XbwHrt87mQ0-unsplash.jpg)



## Project Overview

This project will use regression modeling to analyze house sales in  King County.

## Data

This project will use house data from King County,Washington that contains data about the features of the houses located in various parts of the county such as bedrooms, size and location that....
<br>
<a href="https://github.com/AmanyaKaren/dsc-phase-2-project/blob/main/data/kc_house_data.csv">kc_house_data.csv - Link to dataset</a><br>
<a href="https://github.com/AmanyaKaren/dsc-phase-2-project/blob/main/data/column_names.md"> Column_names.md - Column descriptions</a>

## Packages Used
1. Pandas
2. Numpy
3. SciKit-learn
4. Stats models
5. Scipy
6. Matplotlib
7. Seaborn


## Business Problem

White Oak Realty is a real estate company based in Vancouver, Washington DC that would like to expand its business operations by venturing into other cities in Washington. As a junior data scientist at the company, I have been tasked with analysing house sales data in King County and building a model that would predict sale prices. The product design team wants to start by purchasing existing houses in the area and remodelling them for re-sale as well as developing new houses and properties. Inorder to achieve this they need to know;

1. What features affect house prices most?
2. Other underlying factors to focus on that might increase sale prices.

### Overview of the Dataset
<br>

![awesome](images\data.PNG)

## Summary of EDA

1. Distribution of Prices
<br>
![](images\price_distribution.PNG)
<br>
2. Features
<br>

![](images\features1.PNG)
<br>

![](images\features2.PNG)
<br>

## Final Model
The final model performed very well employing methods such as log transformations on numerical variables and in the end selecting the best features by running a sequence of models and dropping features based on their p-values to finally arrive at the features with the most significant relationship with price.


## Summary of Findings 
<br>

![](images\conclusion.PNG)


<a href="https://github.com/AmanyaKaren/dsc-phase-2-project/blob/main/data/student.ipynb">See more on this project - Link to Jupyter Notebook</a><br>