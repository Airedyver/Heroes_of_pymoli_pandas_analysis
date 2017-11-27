# pandas
Findings:
Converting between dataframes to series to whatever else is near impossible, and then trying to put it all into a table just isn't going so well. 
Probably should not have procrastinated so long on this particular homework. 
Got as much as I possibly could get done but did not necessarily want to go bald because no matter how much I have looked at stack overflow and documentation nothing seemed to work.
What I could Do:
**Player Count**

* Total Number of Players

**Purchasing Analysis (Total)**

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

**Gender Demographics**

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

**Purchasing Analysis (Gender)** 

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Normalized Totals

**Age Demographics**

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.) 
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Normalized Totals
  
  What I could NOT accomplish: 
  **Top Spenders**

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

**Most Popular Items**

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

**Most Profitable Items**

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value
  
  What I tried to get it accomplished: 
  Changing series to dataframes, but when I merged dataframes to get a table I just got a garbled mess. 
  Converting dataframes to series using iloc, but what happened is I could not put the series into a dataframe, also purchase count would either comeback super garbled, or it was sorted different than anything else. I was using value_counts in order to find the purchase count, I did not real feel like there was anyother way to try to obtain this data. I know I tried way more than this, but those are the errors I could honestly understand. I have spent 5 hours just trying to figure out how to make a table for the top 5 spenders. 
  Obviously this problem could be done, else you would not have given it to us right? RIGHT? 
  