# DataPrepAutos
Script that ingests, cleans, and transforms data to prepare it for modeling.

- Used pandas to laod in and view the data in conjuction with Seaborn to explore the dtaa further and find any correlations or missing values
- Used Scikit Learn to create transformers and encoeder to better prepare the data for modeling
  - Example of an import used throughout this notebook was *Pipeline* which was imported from the sklearn.pipeline library, and used to transform both numerical and categorical data
- The data at the end is ready to be used in a model to predict MPG 
