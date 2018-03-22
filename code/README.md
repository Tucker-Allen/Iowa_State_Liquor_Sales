# Repo Layout

- README.md
- code
  - README.md (this file)
  - TuckerMagic.ipynb
  - starter-code.ipynb
  - starter-code-full-data-set.ipynb
  - iowa_pop_clean.csv
- data
  - iowa-zip-city-county
  - iowa_pop.csv
  - iowa_test.csv
  - iowa_full.csv

---------------------------

# Datasets:
iowa-zip-city-county:
	This dataset was circulated courtesy of Corey Girard (DSI+/3/NYC)

iowa_pop.csv:
	This city population dataset was taken from
	https://en.wikipedia.org/wiki/List_of_largest_Iowa_cities_by_population

iowa_test.csv:
	This dataset is a 10% sample of iowa_full.csv

iowa_full.csv:
	This dataset was provided by GA for the purpose of the project

iowa_pop_clean.csv
	This file was created within starter-code.ipynb in case I wanted to export a useful population 

-----------------------

# Summary:
A Linear Regression model, with and without Ridge Regression regularization, was explored in order to best predict total Annual Sales for 2016 at Iowa State Liquor Stores. The Ridge Regression model yielded a test score of 0.987, indicating that the model describes a significant amount of the variance in the training/test data, so we can reasonably rely on its predictions of 2016 Annual Sales. 2016 Annual sales were predicted to be $289,740,820, which is a slight increase of 1.9% over the previous year in 2015.