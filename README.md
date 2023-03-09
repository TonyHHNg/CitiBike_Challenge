# CitiBike Challenge
![citi-bike-station-bikes](https://user-images.githubusercontent.com/116006523/224065327-cacb2923-3852-405e-9f69-0e56b0451a1f.jpg)

## Background 

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Data](https://citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

3. Create one of the following visualizations for city officials:

    * **Basic**: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

    * **Advanced**: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

    * The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

4. Create your final presentation:

    * Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

    * Ensure your presentation is professional, logical, and visually appealing.
    
## Data Source

1. Data was collected from the [Citi Bike Data](https://citibikenyc.com/system-data) webpage and stored in file "resources". 

2. Jupyter Notebook file, named "Starter Code" is to carry out cleansing process and merge for the CSV files into a single CSV file, in preparation for importing into Tableau.

### Dashboards
From the CitiBike data, a homepage and two corresponding dashboards were created to provide a comprehensive analysis and visualization of the data.

### Homepage
* The homepage act as an introduction to the project, providing a concise overview of its purpose and contents. It clearly summarizes the key insights and findings of each dashboard, allowing for quick and easy navigation.

### User Analysis 
* In this section, presents an analysis of the Citi Bike trips, user types, basic numerical information of the system. In addition, showing trend of users taking trips within the timeframe and graphs showing respective ridable types. 

### Station Analysis
* In this section, focusing on the analysis of trips in relation to the stations. It compares the patterns between weekdays and weekends within the timeframe and showing the TOP 10 Start and End Stations. 


### Map Analysis
* In this section, presents two maps showing TOP 20 popular geographical locations of the start and end stations. The sizes and colors of the markers represent the total number of trips at each stations with zip code data overlaid on top.

## Summary
![basic information ](https://user-images.githubusercontent.com/116006523/224081644-acb6c0e5-38d2-4ceb-b4e4-55c591d5cb85.jpg)

* Data covering the time period from August to December 2023 shows a total of 14,283,254 trips made using bicycles in New York City. The total number of start and end stations are 1,718 and 1,719 respectively. 

![Total Trips per month ](https://user-images.githubusercontent.com/116006523/224083370-d58cc8e6-e3d2-4480-abe6-eaa74e4f1943.jpg)

The bar chart shows total trips within the time preiod and filtered by types of bicycle customer used. Significantly, classic bikes are the most used following by electric bikes and docked bikes. The reason of choosing the data with this preiod is to investigate if weather would affect users' choice of transportation. Below trend line clearly shows that from August (Summer/ Autumn) to September (start of Winter), uses of citibike started to drop and dropped significantly in the period of October to December (Almost half). As result, these two graphs show waether could be one of the factors affecting the number of bike uses. 

![Total Trips per month (trendline)](https://user-images.githubusercontent.com/116006523/224083394-24f59a90-5f4b-4aaa-acbb-302697e2f23d.jpg)


* The peak utilization of citibikes in New York City occurs during the weekday (Wednesday), specifically during the hours of 8 a.m. and 5 p.m., as a significant number of commuters utilize bicycles for their daily commute. The colour shows the uses (from green to red). Please see belowq heat map and bar chart comparing months, weekdays and weekends. 

![Hour Heatmap](https://user-images.githubusercontent.com/116006523/224092264-ee695702-de34-485f-84e4-b67093ea3634.jpg)

![Weekday and weekend ](https://user-images.githubusercontent.com/116006523/224093332-b384fec9-47f9-44eb-824d-4526c4d37eb5.jpg)


* The data shows a disparity in the number of start stations compared to the number of end stations.

![Top 10 End](https://user-images.githubusercontent.com/116006523/224094059-9c62eb38-57c9-4827-b308-98075c771bac.jpg)
![Top 10 Start](https://user-images.githubusercontent.com/116006523/224094133-cbc58958-2b59-42c5-9d50-27c9f284b374.jpg)
![Top 10 Start and End ](https://user-images.githubusercontent.com/116006523/224094231-0edc47ad-3649-4e2c-bcc5-fd8d20c7bb0e.jpg)

* The analysis of the data, as depicted in the chart, indicates that W21 St & 6 Ave are the most frequently used stations for both starting and ending trips.

![Start map](https://user-images.githubusercontent.com/116006523/224097918-fccb6cf6-a125-49e4-9485-5713fbbdddc0.jpg)

* An analysis of the start station map highlights the concentration of the most frequently used stations in Jersey City, New Jersey, primarily in the zip codes 10011 and 10018. This suggests that the residents or users would choose CitiBike service instead of other public transport. 

![End map](https://user-images.githubusercontent.com/116006523/224097952-657fb78f-0bf4-4b7a-bee1-bf55c37bbf94.jpg)

* Similar to the start station map, the end station map also illustrates a notable concentration of the most frequently used stations with zip code 10011 and 10018 shows that residents or users are likely choose CitiBike service instead of other public transport. 

## Conclusion
As conclusion, in this challenge, the original data set was supposed to be within the timeframe July to December to look for a trendline from summer to winter but Tableau public could not proceed with over 15,000,000 data, therefore the chose of data would have been affect the accuracy of the phenomenon discovered. 

This challenge overall overviews the trends and patterns in Citibike usage over a specified timeframe. Through creating dahsboards, story and homepage gives me more chance to explore tableau functions. 

One interesting phenomenon observed within this challenge is the high usage of the Citibike service within the New York Area. Look forward to explore and dig deeper with tableau. 

