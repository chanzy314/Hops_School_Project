# DATA 115 Personal Dataset project on Hops


## Motivation: 
   My motivation is pretty simple I enjoy plants and agriculture. I enjoy driving country roads seeing farms and the different techniques of how different plants are grown in large quantities. I especially enjoy seeing hops plants because they are vines that are suspended upward by 25 foot poles that creates an amazing canopy. I also like beer, and since Washington State is also known for it's hoppy beer I got curious about where the hops come from. That is when I discovered that all of the hops grown in the United States were grown in only 3 states, Washington, Oregon and Idaho. Which got me to thinking, if I wanted to grow an acre of hops, in what state and what type would I need to grow in order for that acre to be the most profitable? 

## Data Process: 
   I found my data at the USDA's website https://usda.library.cornell.edu/concern/publications/s7526c41m where I downloaded the csv files with the data from 2018-2020 production of different types of hops, yield and prices of hops grown in Idaho, Oregon, and Washington. 
   In order to work with the data effectively, I needed to rearrange some columns in the excel worksheets so that each year went to individual columns next to each other in the file. I also erased any cells that had (D) or (NA) because they had no useful information and made the calculations in rstudio difficult. I merged the price per lb information from the Hops Price Table to add price columns for each year. I also erased rows that had more then one type of hop since I wanted to know what the highest grossing singular type was. I then created the Gross Profit column for each year by multiplying the yield per acre column by price column. This gave me the information I needed to work with in order to create the visuals below. After the data manipulation I uploaded this CVS file https://github.com/chanzy314/Hops_School_Project/blob/main/Hop%20Data%20with%20Prices.csv to rstudio an made my evaluations. 

## Visualization: 

Below are the scatterplots of the profit per acre by State for 2019 and 2020.


<table>
   <tr><td>
      
![image](https://user-images.githubusercontent.com/61097093/115101153-aefea700-9ef6-11eb-99ae-31738decfba7.png)
      
</td><td>
      
![image](https://user-images.githubusercontent.com/61097093/115101161-c047b380-9ef6-11eb-9e87-207d2248e43a.png)

</table>

## Analytical Technique: 

Below are the "Top Ten Plants for 2018-2020. The biggest thing I learned while doing this assignment was to not make assumptions. While I was working with the data, I had assumed the the greatest yield per acre automatically meant that that would mean the greatest profit. I forgot to take into consideration that each state had different buy prices. This explains the scatter plot for 2019 where you can see the deviation between each state. In 2019 Idaho price was $5.25 a pound wheras Oregon was $5.50 and Washington growers got $5.80. The year 2020 was an interesting case. The prices went up in all states Idaho getting $5.80lb and Washington and Oregon getting $6.00/lb.      

<table>
<tr><th> 2018 Top Ten </th><th>2019 Top Ten </th><th>2020 Top Ten</th></tr>
<tr><td>

| State | Type | Gross Profit|
| --- | --- | --- |
|WA|	Bravo TM |	17919.0	|	
|WA	|Super Galena TM	| 17231.5	|	
|WA| Eureka! TM	| 16247.0		|
|WA	| Apollo TM	|15664.0		|
|WA|	Ahtanum TM|15015.0|		
|ID	|Zeus 1 |	14649.2		|
|WA	|Zeus 1|14404.5	|	
|WA	|Ekuanot R	|14206.5	|	
|WA|	Azacca TM|	13700.5	|	
|WA	|Palisade R	| 13425.5	|


</td><td>

| State | Type | Gross Profit|
| --- | --- | --- |
|WA|	Bravo TM	|18652.8		|
|WA|	Eureka! TM|	18490.4		|
|WA|	Super Galena TM	|16651.8	|	
|WA|	Ahtanum TM|16356.0|		
|WA|	Apollo TM	|15863.0	|	
|WA|	Zeus 1	|15196.0		|
|WA|	Palisade R|	14616.0	|	
|WA|	Ekuanot R	|14401.4	|	
|WA|	Azacca TM	|14157.8	|	
|ID|	Zeus 1	|14028.0	|

</td><td>

| State | Type | Gross Profit|
| --- | --- | --- |
|OR|	Super Galena TM|	16806.0	|	
|WA|Super Galena TM	|15816.0|		
|ID|	Idaho 7 TM	|14163.6	|	
|OR	|Amarillo R	|14160.0	|	
|WA|	Eureka! TM|	13992.0		|
|WA|	Bravo TM|	13848.0		|
|OR	|Liberty|	13734.0		|
|ID	|Mosaic R|	13543.0|		
|WA	|Apollo TM	|13488.0	|	
|WA	|Ekuanot R	|12948.0	|

<tr><td></table>


• Presentation: In the final week of class, you will give a three minute presentation3 about your
dataset and repository


