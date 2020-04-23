## Day 03 | April 23, 2020 | Thursday
Today's progress:
- Learning Pandas:
  + Creating dataframe, series
  + Reading, and writing file
  + indexing, manipulating the index,

## Day 02 | April 22, 2020 | Wednesday

Today's progress:
Model validation
- Mean Absolute Error: error = actual - predicted
- Validation data
- Split data: from sklearn.model_selection import train_test_split
- underfitting vs overfitting
- random forest model

## Day 01 | April 21, 2020 | Tuesday

Today's progress:
- Setting up todayilearned100days repo
- Choosing courses in kaggle.com and courses.analyticsvidhya.com

What I have learned:
- Using pandas to get familiar with the data
  + open csv file with pd.read_csv
  + print summary of the data with data.describe()
  
 - Selecting data for modelling
  + see list of all columns in the dataset with data.columns
  + drop missing values with data.dropna(axis=0)
  + select thee prediction target with dot-notation: y = data.Price
  + choose features
 - Building the Model with sklearn
  + Define: what type of model will it be?
  + Fit: capture patterns from provided data. This is the heart of modelling
  + Predict
  + Evaluate: Determine how accurate the model's predictions are.
  + decision tree
