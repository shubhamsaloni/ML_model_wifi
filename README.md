ML Model to predict user load on a Wi-Fi network

Goal: Using Logistic Regression model to predict the user load on the Wi-Fi network. 

Data Source : 

https://data.penrith.city/explore/dataset/presence-aggregation/information/?disjunctive.dayofweek&disjunctive.device_name&disjunctive.year&disjunctive.month 

Description:

Purple wifi visitors count - hourly aggregation This data has been generated and sourced from Telstra Purple, data represents counting the number of Wi-Fi signals emitted by non-identifiable mobile devices within a specified proximity and performing certain filtering and processing. It provides an indication of trends, activities and events within access point areas. It can be visualised on our People Counting dashboard.

Anyone using this data does so at their own risk. To the full extent permitted by law, Council is released from and will in no way be liable to you or anyone else for any loss however caused (including through negligence) suffered directly or indirectly as a result of any reliance on this data. All intellectual property rights are reserved.

Counting method: each device in counted only once within a given hour, however the same device can be counted multiple times within the same day. For example:

if the same device is identified twice at 715am and 730am, it is counted as one if the same device is identified at 715am and 815pm, it is counted twice

Outcomes from analysis by this ML model:

Capacity Planning: Area with high user load can be deployed with more or high capacity Wi-Fi access points, and those with lower load with low capacity. We know which are what from shap analysis
Maintainance Window: Looks like a sunday in Jan will be best to do maintainance . And if a mid-year maintainance is needed a sunday in Sep will be good.
