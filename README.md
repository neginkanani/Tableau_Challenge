# Tableau-Challenge

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. 
Each month, bike data is collected, organized, and made public on the Citi Bike webpage https://citibikenyc.com/system-data

I have opened, read, and saved all these data using python. To avoid creating a very large file for each month of data I have read
every 1000 line and combined all these info into one csv file called combined2.csv.

I have then opened the csv file in Tableau and conducted my analysis.

In the Citi Bike story you'll find multiple visualization of my analysis:

1- A map with zip code information showing all the start stations over the years from 2013 till March 2023.
2- A map with zip code information showing all the end stations over the years from 2013 till March 2023.
3- Interactive dashboards were you can pick the month and year and find the top 10 start and end stations, as well as bottom 10 start and end stations.
	 Looking at the results top 10 start and end stations are mostly south of the central park specially in zip codes 10010, 10011, and 10001.
	 Looking at the results bottom 10 start and end stations are mostly outside Manhattan area.
4- Figure describing distance in miles and average distance bikes traveled every year.
	 Looking at this figure since 2013 more customer use the Citi Bike service.
	 The increase was more obviouse in 2020 due to covid as people prefered riding the bike than taxi and train for saftey reasons. 
5- Figures showing the peak hours in summer and winter time
	 Citi Bike's were used more frequently between 5 to 7 pm.
6- Figure describing average trip duration per customer age
	 Younger customers ride the bikes for longer time
7- Interactive dashboard showing the percent growth of the Citi Bike year by year and the percentage of subscribed vs unsuscribed users
	 The most growth in the industry was between 2014 to 2015 of 269%. 2013 and 2023 data should be excluded since they are not complete and lack certain
	 months of data

8- Box plot showing variability in distance every bike traveled per trip
	There are instances that a bike traveld up to 8 miles but on average bikes travel around 1 mile per trip

9-Bubble chart showing the total traveled distance for each bike and the bikes that are most likely due for repair in red
