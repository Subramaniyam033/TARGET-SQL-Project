# TARGET-SQL-Project
**Problem Statement:**
	Target seeks to improve its operations and customer experience in Brazil by analysing historical order data FROM 2016 to 2018. The objective is to uncover insights related to order fulfilment, pricing, payments, shipping, customer behaviour, product performance, and reviews. These insights will help Target enhance operational efficiency, optimize pricing and delivery strategies, and improve customer satisfaction to strengthen its position in the Brazilian retail market.

**Data Analysis Insights: (To view the SQL Query kindly view the "SQL Business Case file.docx" file)**
* First order was at 4th September 2016 and the Last Order was at 17th October 2018
* Order details of Customers from total of 4119 city from 27 states
* Highest order count was at November 2017 followed by January to May of 2018
* Overall, August, May and July month contributed highest order count whereas September and October contributed less order count
* Though we had order details till October 2018 still 2018 contributed highest order counts of 54,011 compare to 2017 with 45,101
* when we compare day-part, a greater number of orders were placed at Afternoon (13 to 18hrs) followed by Night and Dawn (0 to 6hrs) has the lowest order count
* When we compare state wise order month on month, state='SP' contributed highest number of orders on August, May and July followed by other states
* State wise customer count, State-'SP' has highest customer count which actually matches with previous observation that 'SP' had the highest order count, RJ and MG were the second and third highest in customer count
* There is increase of 143% in Order value at 2018 compare to 2017 which matches with the last observation that 2018 has highest order count compare to 2017
* while observing Payment value it’s clear that 'PB' has the highest average payment value followed by AC and RO state.  In terms of Total value state-'CE' is the highest
* RP, PB, RO were the top 3 in highest Freight value
* SP, PR, MG were the top 3 in lowest Freight value
* SP has the lowest delivery time of 8.3 which in return reflects in highest sales and order count followed by PR with 11.53 and MG with 11.54
* PR, AP and AM have the highest delivery time of above 26
* In states AC, RO, AP, AM and RR actual delivery date is faster than the estimated delivery date
* Highest number of orders were done through credit card followed by UPI and then vouchers and Debit card
* Top 3 payment installments basic of order counts are 1,2,3 with total of 75k orders 
placed and lowest was 22 and 23 with only one order

**Recommendations for Target:**
**Sales and Region Focus:**
* Focus sales and promotions in high-performing states: SP, RJ, MG
* Expand campaigns in mid-tier but high-value states: CE, PB, RO
* Leverage customer density in SP to test new products and loyalty programs
**Logistics and Delivery Optimization:**
* Reduce delivery times in slow regions: PR, AP, AM (over 26 days)
* Update estimated delivery dates where actual delivery is faster: AC, RO, AP, AM, RR
* Replicate SP’s logistics model (8.3-day average) in other regions for improved efficiency
**Payment Method Strategy:**
* Promote Credit Card and UPI options — top 2 payment methods
* Focus on 1–3 installments options, which account for ~75% of orders
* Avoid complex installments options (20+), as they have minimal adoption
**Time & Season-Based Marketing**
* Run sales and campaigns during peak ordering times: Afternoon (13–18 hrs)
* Maximize campaigns in high-order months: August, May, July
* Plan November promotions, leveraging past success (e.g., Black Friday bump)
**Order Value Optimization**
* Explore high average payment states: PB, AC, RO for premium offerings
* Offer premium bundles or loyalty perks targeting high-value regions
**Inventory & Demand Planning**
* Align inventory forecasting with 2018’s 143% YoY order value growth
* Prioritize stock placement in high-demand states: SP, RJ, MG
**Localized Operational Strategy**
* Develop state-specific dashboards for delivery, payments, and order trends
* Assign regional leads to tailor strategies based on local performance

