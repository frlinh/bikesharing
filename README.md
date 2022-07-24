# An analysis of Citi Bike data in NYC

## Project Overview
Performed data analysis on NYC Citi Bike data from August of 2019 to determine whether investors should invest in a bike-sharing program in Des Moines, IA.  We will examine the average trip duration by birth year, customer types, top starting and ending trip locations, peak hours, non-peak hours for bike maintenance and repairs, and bike utilization.

## Resources
- Data Source: [CitiBikeNYC](https://ride.citibikenyc.com/system-data), 201908-citibike-tripdata.csv
- Software: Jupyter Notebook, Tableau

## Summary
Tableau: [NYC Citi Bike Dashboard](https://public.tableau.com/shared/WKDKPFYPP?:display_count=n&:origin=viz_share_link)

The analysis of the Citi Bike data shows that:
- The Citi bike-sharing program generated over 2.3 million rides in the month of August with a total of 13,983 bikes
- The percentage of subscribers is 81% and the percentage of customers is 19%
- The percentage of male bike riders is 65%, female bike riders is 25%, and unknown bike riders is 10%
- The top three starting and ending locations are Pershing Square North, East 17th St. & Broadway, and West St. & Chambers St.
- The peak hours are from 7 AM to 9 AM and 5 PM to 8 PM on weekdays during commuting hours
- The top users are male subscribers

![Dashboard](https://github.com/frlinh/bikesharing/blob/0abad434d2abd8b1d965ed825d9057a6e8a99540/Resources/NYCBikeDashboard.png)

![Top_Locations](https://github.com/frlinh/bikesharing/blob/0abad434d2abd8b1d965ed825d9057a6e8a99540/Resources/topLocations.png)

![Trips_by_Gender](https://github.com/frlinh/bikesharing/blob/0abad434d2abd8b1d965ed825d9057a6e8a99540/Resources/usersGender.png)

### Bike Maintenance & Repairs
- The optimal time for maintenance and repairs is between 1 AM to 6 AM

![Bike_Repairs_All](https://github.com/frlinh/bikesharing/blob/9b9456a291c7f9ca5beafba8335924db4ff5939c/Resources/bikeRepairsAll.png)

![Bike_Repairs](https://github.com/frlinh/bikesharing/blob/c17f45bb57104e3040ff31ffb12be42cbb61fea5/Resources/bikeRepairs.png)

![NonPeak](https://github.com/frlinh/bikesharing/blob/bb114d8d2fa4f66d9ac25851b34b7d8284cde6b5/Resources/nonPeakTimes.png)

### Bike Utilization
- The bike utilization time ranges from 70 to 3,838,467 seconds
- There's an imbalance in bike utilization

![Bike_Utliz](https://github.com/frlinh/bikesharing/blob/9b9456a291c7f9ca5beafba8335924db4ff5939c/Resources/bikeUtilization.png)

![Bike_Utliz](https://github.com/frlinh/bikesharing/blob/9b9456a291c7f9ca5beafba8335924db4ff5939c/Resources/bikeUtilizationFiltered.png)

### Additional visualizations are recommended for future analysis

1. Trip locations map based on birth year to examine age group by area
2. Trip duration treemap to examine how long each bike is used, and mark which ones are most frequently
