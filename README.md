# Surfs_Up

## Analysis
The purpose of this analysis is to provide information about temperature trends before opening a surf shop in Oahu, Hawaii. Specifically, providing temperature data for the months of June and December because those are detrimental months in Hawaii for opening a Surf and Ice Cream shop. This information will let us know if opening this business will be sustainable year-round.

## Results
* To retrieve the data needed for the weather  I had to write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June and december. 
![june_query.PNG](/june_query.PNG)

* In the first deliverable we had to gather the weather information for the month of June. I pulled all the weather data for June form 2010 to June 2017 for every single day of the month. The information returned in as a series and I converted the data inot a list. From a List i converted the data into a DataFrame which can give a better sum of all the years. 
### June Weather 2010-17
![June_weather.PNG](/June_weather.PNG)


* In the second deliverable I used the same format I used for the first deliverable but only for the month of December instead. Coverted the data into a DateFrame.

### December Weather 2010-17
![December_weather.PNG](/December_weather.PNG)

## Summary

High-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

From what I gathered from the data I believe opening a Surf and Ice Cream shop would be a great idea. The worst months are June and December. June it doesn't get colder than 74 degrees. I don't believe 74 degrees is too cold to have ice cream or to go surf. Also June is a travel month for the summer. So you may have international people traveling from colder areas to be tourist in that month. December the coldest it gets is 65 degrees. That may be a bit chilly but it's still not too bad. You'd really have to only prepare to have one shaky month throughout the year. Two other queries that I feel would be beneficial to the weather climate data would be first, a query of the population in the area of Oahu. So you can get an idea of how much traffic you may get from locals. That query can also tell you how many tourist are coming to the the store and who to target towards. The second query I believe would be beneficial would be a query of the flavors of ice cream and surf boards they're selling. It'll be best if they did local surveys in the area before opened. So you can have a better idea of supply and demand to your targeted areas. 
