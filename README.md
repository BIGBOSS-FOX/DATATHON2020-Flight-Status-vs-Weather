# Data Analysis and Modelling on The Relationship between Weather and Flight Status
***Project in the finals of 2020 CHINA ONLINE DATATHON, 07/2020***
**Passed the 5000-people preliminary and qualified for the finals. Data used in the finals is provided by organizers and the direction of the project was designed by myself**
- Imported ‘weather.csv’ and ‘flight_traffic.csv’ into pandas.DataFrame
- Analyzed and visualized raw data and performed data cleaning on abnormal and NaN values
- Dropped meaningless features and altered data expressions and types based on certain conditions
- Merged ‘df_weather’ with ‘df_flight_status’ by matching corresponding keys such as ‘datetime’ and ‘airport_id’
- Performed one-hot encoding on categorical features and min-max normalization on numerical features
- Used the processed data to train a Random Forest machine learning model with sklearn
- Used the trained model to predict on test set and achieved an accuracy of 95%
- Performed visualization analysis on related weather factors and found how each of them attributed to the prediction of flight status.
