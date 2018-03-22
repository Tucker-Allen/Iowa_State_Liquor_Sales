# Iowa State Liquor Sales Predictions
Predicting Annual Iowa State Liquor Sales based on Q1 Data

See blog post here: https://tucker-allen.github.io/iowa_liquor_blog/

---

## Repo Layout

- README.md
- code
  - code_10percent_dataset.ipynb <-- Where I got my code working, testing on only a portion of the dataset
  - code_100percent_dataset.ipynb <-- Where I executed my final code on entire dataset
  - TuckerMagic.ipynb <-- Some custom functions I wanted available during EDA
- data
  - iowa-zip-city-county <-- Not included on GH for size constraints
  - iowa_pop.csv <-- Not included on GH for size constraints
  - iowa_test.csv <-- Not included on GH for size constraints
  - iowa_full.csv <-- Not included on GH for size contraints
  - iowa_pop_clean.csv

---------------------------

### Datasets:
iowa-zip-city-county:
	This dataset was circulated courtesy of Corey Girard (DSI+/3/NYC), and relates Iowa City/Zip Code/County

iowa_pop.csv:
	This city population dataset was taken from:
	https://en.wikipedia.org/wiki/List_of_largest_Iowa_cities_by_population

iowa_test.csv:
	This dataset is a 10% sample of iowa_full.csv

iowa_full.csv:
	This dataset is made available by the state of Iowa here:
  https://data.iowa.gov/Economy/Iowa-Liquor-Sales/m3tr-qhgy

iowa_pop_clean.csv
	This file was created within code_10percent_dataset.ipynb for circulation

-----------------------

## Summary:
A Linear Regression model, with and without Ridge Regression regularization, was explored in order to best predict total Annual Sales for 2016 at Iowa State Liquor Stores. The Ridge Regression model yielded a test score of 0.987, indicating that the model describes a significant amount of the variance in the training/test data, so we can reasonably rely on its predictions of 2016 Annual Sales. 2016 Annual sales were predicted to be $289,740,820, which is a slight increase of 1.9% over the previous year in 2015.