# FINAL PROJECT (DAKOTA BRUBAKER).




#### For this final project I chose to look at a FiveThirtyEight data set on police killings in 2015. 
#### Here is a link to the original article from [FiveThirtyEight](https://fivethirtyeight.com/features/where-police-have-killed-americans-in-2015/).


#### I chose this data set for two reasons:
1. Although the data set is slightly older knowing how to 
ask questions around a topic as relevant as police shootings is important. 
2. FiveThirtyEight is a reliable source for data with lots of information. 


#### The data set includes 468 recorded police killings in the United States from 2015. For each killing by police the CSV file gives information on: 
* **The victim** of police violence _(age, race, gender, name)_
* **Location** _(Long, Lat, City, State)_
* **Demographics** where violence occured _(data on the census track/city where the killing occured)_

As I first started looking at the data I had some initial questions: 
* What were the situations around these Americans being killed by the police? 
* Where was with violence against citizens happening? 
* Who was being affected by this? 

I started my investiation of the data by first using Google sheet filters to get a feel for what the age range of victims was, what was the highest and lowest medium income where violence occured, and what states appear most on the list. 
Just from my initial observations I noticed CA appear an impressive amount so I decided to start with this observation and make a pivot table. 

I then made a pivot table where I created rows for: 
1. **State**
2. **Name** 


Here is an image of my pivot table: 


![Pivot Table 1](/Users/dakotabrubaker/Desktop/PIVOT_TABLE_1.png 
)








I then used a values filter using ```= COUNTA() ``` for each state to find out what percentage of the total each state made up. 

The following is the graph I got from this process: 



## Percentage of Killings by State
This graph shows for each state what percentage of Americans killed by police occured in that state.


![Graph for State Percentage Shooting](https://docs.google.com/spreadsheets/d/e/2PACX-1vQw0hyjwUqtaHscofgS01TQXBX2abllsGuYY9bb-Dju2f1KHYEXRU_cXjuhTPh_IWsI7NRYz2tEzT5x/pubchart?oid=954737982&format=image)


I saw from this graph that for the percentage for CA **(15.85%)** was actually the largest out of the entire US in 2015. From here I thought okay I can investigate one of my other questions about what is the socioeconomic situation around these killings in regards to CA. 

So from here I made a new sheet titled 'CA Median Income'. 


## 2015 POLICE KILLINGS 


First was curious about what states experienced the worst percentage of killings. 


Ended up being CA. 


<iframe title="Police Killings (2015)" aria-label="map" id="datawrapper-chart-ewVqG" src="https://datawrapper.dwcdn.net/ewVqG/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="677"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## DEATHS BY AGE 


Pivot table 



```
= SUM()
```


Creating a chart

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQw0hyjwUqtaHscofgS01TQXBX2abllsGuYY9bb-Dju2f1KHYEXRU_cXjuhTPh_IWsI7NRYz2tEzT5x/pubchart?oid=1943199288&amp;format=image"></iframe>




## CA COUNTIES BY MEDIAN INCOME 

Decided to further investigate by creating a new sheet that tracked CA counties where killings occured to that counties Median income. FiveThirtyEight article had mentioned that there was a relationship between poorer census tracks and deaths. So I started by creating this map on [DataWrapper](https://www.datawrapper.de/). 




<iframe title="CA COUNTIES" aria-label="map" id="datawrapper-chart-WsyMe" src="https://datawrapper.dwcdn.net/WsyMe/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="748"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## US COUNTIES BY MEDIAN INCOME


<iframe title="US COUNTIES WITH MEDIAN INCOME" aria-label="map" id="datawrapper-chart-PlgdB" src="https://datawrapper.dwcdn.net/PlgdB/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="564"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
