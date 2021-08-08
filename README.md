# Surf's Up Climate Statistical Analysis  
  
  * Analyst: Stan Misina. 
  * Source Data: SQLite database provided by client with data from 2010 forward: **`hawaii.sqlite`**.  
      - containing data from 9 stations around Ohau, from Jan 1, 2010    
      - measurements available: temperature observed, and precipitation amounts
  * Source Code: Python v. 3.8.10 built in Jupyter Notebook 6.4.0. 
  
## Overview Statistical Analysis  
  
Clent requests information about temperature trends -- specifically, temperature data for the months of June and December in Oahu. This data will be key in determining viability of proposed surf and ice cream shop for year-round business.  The sample size is appropriate to make this analysis.  
  
  
### Results  
  
![june_results](readme_resources/june_temps.png)
![dec_results](readme_resources/dec_temps.png)
  
Analysis yeilded these specific findings:  
  
* June is a warmer month with the data's low temperature of only 64&deg;F and a pleasant average temperature of 75&deg;F  
* December is a cooler month with a mult-year low temperature of 56&deg;F, the low average at 69&deg;F 
* Hawaii's average temperature when solely in view of June and December results, varies 3.5&deg;F 


### Summary  
  
Surfing in Hawaii is a four seasons enterprise. The client mentioned how previous ventures were "rained out of business," which brings up another climate indicator: precipitation. When considering ice cream sales, temperature and precipitation could have an affect. 
  
Analysis below is a multi-year month by month break down of temperature and precipitation. When planning a year-round business model, ice cream business sales velocity could be affected in the winter months after December. Average temperatures for January through March are lower than any other points in the data. In addition, March and December average the most rainfall. In managing operating and labor costs, the client should take this into consideration regarding hours open, and being agile during these potentially difficult months.

The first graph shows averages for temperature and rainfall. Take note of the monthly trends with combined data dating back to 2010. Likewise, the analyst prepared an outliers graph, to show months where extreme precipitation and coolest temperature has occurs since 2010. Note again the results of December through March. Consideration should be given to the business model, schedule, and open days during this period. Solely considering June and December would not reveal this potential issue for a four seasons business.<br/>
  
  
![averages](readme_resources/year_average.png)
![outliers](readme_resources/outliers.png)  

