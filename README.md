# DoorDash Project

#### Link to Dataset
https://tinyurl.com/m45ukevh

#### Data Set Background
The data set is about the transactions of DoorDash delivery service operating in three regions of the United States: Palo Alto, Mountain View, and San Jose. It includes 14 columns such as customer-placed order DateTime,customer_id, restaurant_id, order total, discount, tip and total time-elapsed (the duration each delivery takes from the time a customer places an order to the moment it gets delivered to the customer's doorstep).

#### Challenges
Some errors were found in the original dataset regarding the total time elapsed. In a case where a customer placed an order on the 31st day of a month at 16:59:17 (time) and it was delivered on the 02nd day of the next month at 19:34:56 (time), the actual total time-elapsed should be 2 days 2 hours 35 minutes 39 seconds. Instead, the original data shows total time elapsed was -29 days +02:35:39.000000000. The same error was found in other orders that were placed on the last days of the month and delivered at the beginning of next month, hence it was fixed before the analysis was started.

#### Excel Functions
Conditional statements such as Nested IF Statements, Dynamic Array Functions such as Sort, Unique, Filter, Spilled Range, Text functions, and Stats functions such as SUMIFS, COUNTIFS are used to analyze the data.

![DD6](https://user-images.githubusercontent.com/106499453/210311627-42a741d2-0db6-44ef-9a1e-ebf69afd38a2.png)

#### Future Considerations
Some deep dive analysis would be further taken if there are some details such as restaurant categories like Japanese, western so that we can find out customers' preferences and popularity throughout different dates and hours.
