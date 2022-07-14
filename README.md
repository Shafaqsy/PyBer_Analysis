# PyBer_Analysis
The purpose of this project is to create a ride sharing summary data frame by city type. Also, a multiple line chart of total fares for each city type. Jupyter notebook is been used to find the outcomes and pandas, numpy, and Matplotlib is imported.
## Results:
### For deliverable 1 I used a groupby() function, count() and sum() method to find a ride sharing summary data by each city type. The given data tells us that there is three types of city Urban, Rural, and suburban. The Urban City type total rides = 1,625, total drivers= 2,405, and total fares=$39,854.38 which is the way higher numbers than the other two city type. Rural city type has the highest dollar amount for Average fare per ride =$34.62 and Average fare per driver =$55.49.
![ride_share_data](https://user-images.githubusercontent.com/107155888/178849496-71ba2fa7-df79-4d9f-9506-8a22bd90154f.png)
### For deliverable 2. 
By  using Pandas skills, i used two functions pivot() and resample(). created a multiple-line graph that shows the total fares for each week by city type. Once we created a pivot table by setting (index = "dates", columns = "type", values = "fare"). we can see the data when there's no fare value, The cell is filled as NaN.
![NAN values](https://user-images.githubusercontent.com/107155888/178849871-a2003678-c58a-4f41-ab76-fcf43bd6b6b2.png)
The loc method is been used to find the date range: 2019-01-01 through 2019-04-28. To get the sum of the fares for each week .resample("W").sum() method is been used. we can plot the graph by using the data frame for each weak. The graph shows the Urban city type line is on the top between the fare ranges $15,00 to $25,00. Suburban city type line is in the middle between the ranges $600 to $14,00. The Rural city type line is at the bootom with the lowest fare ranges between $0 to $500. 'Rural areas seem to be underserved and customers in those areas face more expensive fares than the other two cities.![week data](https://user-images.githubusercontent.com/107155888/178850028-81a519fc-1a70-4dd8-a4ef-0a4a5922d6c1.png)

![graph](https://user-images.githubusercontent.com/107155888/178850172-0f798cc1-af9d-4fde-9653-3d1b14ede66d.png)
## Summary
### Recommendations:
As we seen in the graph Urban city type is on the top fare ranges. Urban  looks like a great performing city type and further investment can be made to it.

Rural seems to be very expensive city type. Their average fare per ride and average fare per driver is much higher than the other two cities. I think the number of rides should be increased and the prices for per rides should be dcrease in rural areas.

Total number of rides and total number of drivers should be increase in suburban city type and future investments can be made to it. The graph shows suburban city type in the middle. The fare ranges can increase in the future if more money is invested in rural city.
