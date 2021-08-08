# Surf's Up Climate Statistical Analysis  
  
  * Analyst: Stan Misina. 
  * Source Data: SQLite database provided by client with data from 2010 forward: **`hawaii.sqlite`**.  
      - containing data from 9 stations around Ohau, from Jan 1, 2010    
      - measurements available: temperature observed, and precipitation amounts
  * Source Code: Python v. 3.8.10 built in Jupyter Notebook 6.4.0. 
  
## Overview Statistical Analysis  
  
Clent requests information about temperature trends -- specifically, temperature data for the months of June and December in Oahu. This data will be key in determining viability of proposed surf and ice cream shop for year-round business.  The sample size is appropriate to make this analysis 
  
  
### Results  
  
![june_results](readme_resources/june_temps.png)
![dec_results](readme_resources/dec_temps.png)
  
The analysis yeilded these specific findings:  
  
* June is a warmer month with a low termperature of only 64&deg;F and a pleasant average temperature of 75&deg;F  
* December is cooler month with a low temperature of 56&deg;F, and the first quartile of results of 69&deg;F 
* Hawaii's average temperature when solely considered only varies +-4&deg;F from the beginning of summer to the dawn of winter  


### Summary  
  
Surfing in Hawaii is a 4 seasons business. The client mentioned how previous ventures were "rained out of business," which brings up another climate indicator: precipitation. When considering ice cream sales, temperature and precipitation have more of an affect. In managing operating and labor costs, the client should take into consideration of adjusting hours in the winter due to a chillier average temperature and precipitation.  
  
Analysis below has in-depth, yearly by month analysis for temperature and precipitation. As you are considering a 4 season business model, ice cream business could be affected in the winter months passed December. Average temperatures for January through March are lower than any other points in the data. In addition, March and December are the rainiest months of the year.

The first graph shows averages for temperature and rainfall. Take note of the monthly trends with combined data dating back to 2010. Likewise, the analyst prepared an outliers graph, to show months where extreme weather historically occurs. Note again the results of December through March. Consideration should be given to the business model, schedule, and open days during this period. <br/>
  
  
![averages](readme_resources/year_average.png)
![outliers](readme_resources/outliers.png)  

