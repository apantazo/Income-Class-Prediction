# Income-Class-Prediction
This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). 
The prediction task is to determine whether a person makes over $50K a year.

dataset: https://archive.ics.uci.edu/ml/datasets/census+income


# EDA 
Firstly, we are doing some exploratory data analysis in order to find key relationships within the data.
  
# Feature Engineering 
Secondly, we are trying to make some transformations like Pre-Processing, Encoding, Scaling, Re-Sampling.

# Feature Selection
Now, we have to find the most important features and/or drop the rest.

# Model Selection
Finally, we are training several models on the train set using cross validation. The best model is been evaluated on the test set.
