# Vehicles_Prediction_TS

Contest Information:
https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-for-iot/True/#LeaderBoard

## Task

To predict traffic patterns in each of these four junctions for the next 4 months.

The sensors on each of these junctions were collecting data at different times, hence you will see traffic data from different time periods. To add to the complexity, some of the junctions have provided limited or sparse data requiring thoughtfulness when creating future projections. Depending upon the historical data of 20 months, the government is looking to you to deliver accurate traffic projections for the coming four months. Your algorithm will become the foundation of a larger transformation to make your city smart and intelligent.

## Data

Variable	| Description
-------- | ------------
ID | Unique ID
DateTime	| Hourly Datetime Variable
Junction| Junction Type
Vehicles | Number of Vehicles (Target)

Submission

Column Name |	Description
ID  | Unique ID
Vehicles | Number of Vehicles (Target)

## Model Used In This Notebook
- XGBRegressor 
