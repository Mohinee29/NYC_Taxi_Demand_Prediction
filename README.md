# NYC_Taxi_Demand_Prediction
Business Problem

For a given location in New York City, the goal is to predict  number of pickups  around that location. Some locations require more number of taxis at peak hours considering a number of factors in that location. By viewing the prediction, the taxi drivers can move to that particular location for increased number of pickups.


Source of Data

Data can be downloaded from here: http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml


Objectives & Constraints

Objectives: 

Our objective is to predict the number of pickups as accurately as possible for each region in a 10min interval. We will break up the whole New York City into regions. Now, the 10min interval is chosen because in NYC one can commute 1 mile in approximately 10 minutes given the traffic is normal at that particular time.

Constraints:

Latency: There is a medium latency requirement ranging from few seconds to minutes.

Interpretability: There is a no interpretability required.A taxi driver is only concerned with the accurate prediction results.

Relative Errors: Mean Absolute Percentage Error will be the relative error we will consider. Our goal is to reduce the percentage error is low as possible.

Acknowledgments
• Applied AI Course
