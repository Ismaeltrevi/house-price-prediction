# Kings County Housing Price Prediction

![seattle](https://github.com/Ismaeltrevi/project-kings_county_housing_prices/blob/main/seattle.jpg)

## Overview

In this project, I created a model that predicts the house price in King County, Seattle with and RMSE of 111078.53 and R-squared of .80. I used data exploration, feature engineering, statistical tests, and modeling to complete this project.

### Business Problem

1. What are the most important variables in predicting the selling price of a house?

2. What variables can we create to make a strong model?

3. Is there any difference in price depending on the month of when a house is sold?

### Deliverables
1. GitHub repository with all the files
2. Jupyter notebook with EDA, Feature Engineering, statistical tests, and model evaluation.
3. Holdout predictions


### Data
The data set was provided by Flatiron School.

### Results

![heatmap](https://github.com/Ismaeltrevi/project-kings_county_housing_prices/blob/main/images/heatmap.png)

The model was able to predict houses with a RMSE of 164078.53 and a R-squared score of 0.80. During the construction of the model, it turned out that most of the variables helped predicting house prices. The features with the highest correlations with price were number of bedrooms, number of bathrooms, and square-feet living space. All the continuous variables helped to create a better model. However, categorical variables did not help as much. Zipcodes was an exception.

![months](https://github.com/Ismaeltrevi/project-kings_county_housing_prices/blob/main/images/month_sold.png)


 It's also interesting to notice that, based on the data, houses sold during hotter months (between March and October) had a higher price than houses sold during colder months. 

### Next Steps

- Use the coordinates to add atributes such as good schools and how close the houses are to big companies and the commercial district.

### Navigation

```
├── .ipynb_checkpoints # checkpoints
├── code # pickle files
├── data #datasets
├── images 
├── notebooks
├── .DS_Store
├── Cleaned-Notebook.ipynb
├── README.md
├── model.pickle
├── model.pkl
├── seattle.jpg
```
