# surfs_up Statical Analysis
## Overview of the analysis: 
The purpose of the surfs_up Statical Analysis is retrieve the temperature data for the months of June and December in Oahu, in order to determine if the "surf and ice cream shop" business is sustainable year-round.For this,I will filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June, then convert those temperatures to a list and create a DataFrame from the list, and generate the summary statistics.I will do same thing to retrieve all the temperatures for the month of December also, then convert those temperatures to a list and create a DataFrame from the list, and generate the summary statistics.After getting summary statics for both months I can analize easily to determine if the "surf and ice cream shop" business is sustainable year-round or not. 

### Results:
I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June, then converted those temperatures to a list and created a DataFrame from the list, and generated the summary statistics.I did same thing to retrieve all the temperatures for the month of December also, then converted those temperatures to a list and created a DataFrame from the list, and generated the summary statistics.After getting summary statics for both months I can analize easily to determine if the "surf and ice cream shop" business is sustainable year-round or not in Oaho. 

* **Summary statistics for the June temperatures**
<img width="150" alt="data-Module-9-Challenge-Image-1" src="https://user-images.githubusercontent.com/90277142/141668276-67ec7f42-098e-4504-8d09-26c56029275c.png">

* **Summary statistics for the December temperatures**
<img width="173" alt="data-Module-9-Challenge-Image-2" src="https://user-images.githubusercontent.com/90277142/141668282-6ba1d31d-cb57-482b-99df-d3c9971e7f2f.png">

These are my Summary Statistics for the june and december temperatures,with the help of these statistics,I can determine if the "surf and ice cream shop" business is sustainable year-round or not in Oaho.  

* The Mean (average) for the june temparatures is 74.9 and for the december temparatures is 71 so we can say that temparure of Oaho is in near 70. so tempature in 70 is good to have ice-cream and do surfing.

* The Minimum and Maximum temparute also help us to determine that opening a "surf and ice cream shop" business is sustainable year-round or not in Oaho. So,you can see in the summary statistics for june temperatures, the min tempature is 64 and max tempature is 85 and  in the summary statistics for december temperatures, the min tempature is 56 and max tempature is 83.So we can see the max temprature is  in 80 so definitily day time have good weather so we can say that opening a "surf and ice cream shop" business is in Oaho is good idea and it will sustainable year-round .

* The Standard Deviation in Summary statistics for the June temperatures is 3.25 which are very less than the Mean(Mean is 74.9),means data are clustered around the Mean.According to that we can say that temparute of Oaho is good through out year. same in december temparures statistics Standard Deviation is 3.7 and Mean is 71. so this is justify that temparures are mostley is  in 70.so it is good temprature to have ice-cream and do surfing.so we can say that the "surf and ice cream shop" business is sustainable year-round in Oaho.


#### Summary:
After Analysing Summary statistics for the June temperatures and Summary statistics for the december temperatures,we can say that the weather of Oaho is good through out year because june is summer month and in summer max temprature is 85 and december is winter month and in winter max temprature is 83.so we can say that weather of Oaho is always good for surf and ice cream shop" business.

*December_temp = session.query(Measurement.date,Measurement.tobs).filter(extract('month', Measurement.date)==12)




Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)
write a report that describes the key differences in weather between June and December and two recommendations for further analysis.
