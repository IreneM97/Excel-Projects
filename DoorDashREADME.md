# DoorDash Project

#### LINK TO DATASET
https://tinyurl.com/m45ukevh

#### BACKGROUND
The data set is about the transactions of DoorDash delivery service operating in three regions of the United States: Palo Alto, Mountain View, and San Jose. It includes 14 columns such as customer-placed order DateTime,customer_id, restaurant_id, order total, discount, tip and total time-elapsed (the duration each delivery takes from the time a customer places an order to the moment it gets delivered to the customer's doorstep).

#### OBJECTIVE
The objective of this analysis project is to provide insights into DoorDash's transaction data in three regions of the United States: Palo Alto, Mountain View, and San Jose mainly 
- To identify the top-performing regions and restaurants in terms of total order numbers, sales, net sales, and average sales per order.
- To analyze tipping behavior across different regions and waiting times to understand customer preferences and identify areas for improvement in service quality.
- To recommend actionable strategies for optimizing operations during peak hours, reducing order refund rates, and increasing sales through targeted promotions.

#### ANAYSIS
![Screenshot 2023-04-11 205928](https://user-images.githubusercontent.com/106499453/231347411-057516b6-6937-421e-bc9b-cc3a3db91095.png)
Out of all three regions; Palo Alto is the most performing region with being the highest in total order numbers, total sales, and net sales, followed by Mountain View and San Jose
![image](https://user-images.githubusercontent.com/106499453/231347517-4b03eeea-8be5-4168-8ea6-488052477957.png)
When examining regional sales data, there appears to be a significant difference between Palo Alto and Mountain View. However, an analysis of average sales per order reveals that they are nearly identical.
![image](https://user-images.githubusercontent.com/106499453/231351079-a8d4e053-a2a7-4725-9dc5-b4751772f82a.png)
Upon initial observation, it appears that customers in the Palo Alto region are the most generous tippers, as evidenced by their ranking first in total tips by region.
#### However, a more detailed analysis of the data reveals that on average, customers from Palo Alto tip $3.44 per order, which is actually the lowest average tip amount across all regions. Conversely, customers from Mountain View tip an average of $3.56 per order, which is the highest average tip amount among all regions.
![image](https://user-images.githubusercontent.com/106499453/231351479-06dededf-124c-4e93-ad21-2f1db8d45506.png)                                                  
Out of all refund orders, 29% occurred within 41 to 60 minutes of waiting time, followed by 19% within 61 to 80 minutes, and 16% within 21 to 40 minutes. It is worth noting that no orders were cancelled under a 20-minute waiting period.
#### This information can be leveraged by the operations team to maintain waiting times under 20 minutes, or optimally, under 40 minutes. By doing so, the rate of order refunds is expected to decrease to 16%.
![image](https://user-images.githubusercontent.com/106499453/231353600-e7d54bc0-b780-45ae-87af-90ae349b2c44.png)                                                     
Conversely, it appears that tip amounts are not significantly influenced by waiting times. In fact, it is somewhat surprising to note that customers tend to leave higher tips for orders that take longer to fulfill.
![image](https://user-images.githubusercontent.com/106499453/231355713-64d6370e-9935-464e-96a8-f5f80c86626f.png)
Hours with the highest order volume are between 12 AM and 3 AM, regardless of the region. 
#### This information can be utilized by our partner restaurants to optimize their operations during these peak hours either by planning for sufficient manpower for that time frame or stocking up on extra inventory to deliver orders promptly. By doing so, restaurants can potentially maximize their sales during these profitable times.
![image](https://user-images.githubusercontent.com/106499453/231359924-6cd088be-b1ca-44ba-ad64-0605361790ae.png)
Regardless of the region, Week 4 consistently records the highest sales figures.
![image](https://user-images.githubusercontent.com/106499453/231365626-11eac692-c630-48e7-930b-21f4d6d473e6.png)
This chart displays the top 10 highest-selling restaurants in each region, which can prove to be a valuable resource for recognizing and rewarding our partner restaurants at the end of the year, thereby helping to maintain positive relationships with them

#### RECOMMENDATIONS
Based on the analysis, the following recommendations are suggested:
#### - Hiring midnight dashers to provide support during peak hours, particularly between 12 AM and 3 AM when order volume is highest, to ensure prompt deliveries and maintain customer satisfaction.
#### - Advising partner restaurants and dashers to prioritize keeping waiting times under 40 minutes to reduce the rate of order refunds to 16%.
#### - Implementing promotional strategies during weeks with slow sales, such as Week 1, 2, and 3, in order to generate higher sales and revenue, similar to the profitable Week 4.

#### Future Considerations
Further analysis can be done if there are some details such as restaurant categories like Japanese, western so that we can find out customers' preferences and popularity throughout different dates and hours.

#### Excel Functions
The comprehensive analysis was conducted using a combination of Pivot Tables, Pivot Table Calculated Fields, Conditional Statements, and Text functions.

