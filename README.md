# CrunchCo-Snacks
CrunchCo Snacks, founded in 2015, is an FMCG retailer selling a wide range of chip and snack products across 271 stores nationwide. 

The company collects data on its sales transactions and customer behavior that has been underutilized. This project thoroughly analyses and synthesises the data to uncover insights that will improve CrunchCo's category performance and customer-targeting strategy. 

Insights and recommendations are provided on the following key areas:

* **Sales Trend** - Evaluation of historical sales patterns over the period July 2018 - June 2019, focusing on Revenue, Transaction Volume, and Average Daily Order Volume.

* **Product Performance** - An analysis of CrunchCo's chip product line by brand, understanding their impact on total sales. 

* **Customer Segment Analysis** - An assessment of how different lifestage and premium customers drive chip purchases, units bought, and price paid.

* **Target Segment Deep Dive** - A focused look at the highest-opportunity customer segment. including brand affinities and pack size preferences.

The Tableau Dashboard can be checked <a href="https://public.tableau.com/app/profile/tram.nguyen6514/viz/RetailsandStrategyAnalysis/SalesDashboard?publish=yes"> here </a>

## Data Structure

CrunchCo database includes two tables: orders and customers, with a total row count of 337,475.

<img width="1028" height="536" alt="image" src="https://github.com/user-attachments/assets/426d1c99-4faa-47c5-9bfe-092d6ad3d6f7" />



## Executive Summary

### Sale Trends:

- Total revenue from July 2018 to June 2019 is **nearly $2M**, with **246,739 transactions** and an **average daily order value of $678**. 

- Monthly sales remained in the **~$138k to ~$144k** range for most of the year.

- December 2018 recorded the highest monthly sales of the year at **~$144,676 with 19,698 orders**, driven by **Christmas shopping**. 

- After the December peak, sales **declined** in January 2019 and **reached the lowest point of the year in February 2019 at $130,036.**

- Sales recovered steadily from March 2019 onward, climbing back towards the yearly average before slightly dropping toward June 2019.

<img width="1685" height="301" alt="image" src="https://github.com/user-attachments/assets/c7b4c115-00ae-4493-aff8-9ce88d1fd95d" />

### Product Performance:

- **Kettle** leads across all months, maintaining strong and consistent sales. **Doritos, Smiths, and Pringles** follow as the next tier, and all four brands account for about **56% of the company's total revenue**. These brands also have peak performance in December and a decline in February.

- **Kettle** is the dominant brand at **$390.24K in total sales** - over **70% higher than the second-placed Doritos ($226.33K).**
  
- **Kettle** remains the leader in performance, with the **highest Average Selling Price (ASP) at $4.98 and an Average Daily Order Volume (ADOV) of 106 orders**. This suggests strong overall sales, driven by its premium pricing and a high quantity purchased per transaction. 

- The three **lowest performing brands** are **Burger ($6.4k), French ($7.39k), and Sunbites ($9.02k)**. They contribute **less than 1% of total sales combined.**

<img width="1690" height="423" alt="image" src="https://github.com/user-attachments/assets/d8b8c3dd-7a42-4ebd-9e20-60bf56c6f944" />

### Customer Segment Analysis:

- Customers are segmented across two dimensions:

** **Lifestage:** Young Singles/Couples, Midage Singles/Couples, Older Singles/Couples, Young Families, Older Families, New Families, Retirees

** **Premium Customer:** Budget, Mainstream, Premium

- The **three highest segments** by total chip spends are Budget - **Older Families (8.69%), Mainstream - Young Singles/Couples (8.18%), and Mainstream - Retirees (8.04%)**. These three groups alone make up over **25% of all chip revenue. **

- **Mainstream Young Singles/Couples and Retirees** have the most customers. Mainstream Young Singles/Couples represent **11.1% of all chip customers**, and Mainstream Retirees **8.9%**. Their high total spend simply comes from **having more people**, **not from higher spend per person.** 

- **Mainstream Young and Mid-Aged Singles/Couples** pay a **higher price** per unit compared to the Budget and Premium counterparts. **Mainstream Young Singles/Couples** has the **highest** average price of **$4.07 per bag**, and **Mid-Aged** has ** $4**. This indicates their impulse purchase behavior - grabbing a preferred product rather than price affordability. 

<img width="1691" height="440" alt="image" src="https://github.com/user-attachments/assets/ca14663a-ca5d-4b44-913e-db5393112ead" />
<div>
  <p>
    
  </p>
</div>

* **Budget Older Familiers** shows a different reason. **Older Families** purchase the most chips per customer, **around 8-9 bags of chips**, and nearly **20,000 orders**, more than any other group. This explains why the Budget Older Families have high total spend, even though they are not the biggest group by customer count, and their average price per bag **($3.75)** is one of the lowest. 

<div>
  <p>
    
  </p>
</div> 

<p align = 'center'>
  <img width="850" height="517" alt="image" src="https://github.com/user-attachments/assets/f4f1ecea-2cf9-4046-bf1d-c9b1f86ec8b2" />
</p>

- Mainstream retirees sit in the middle. They buy a reasonable number of bags (5.61 per customer), pay a fair price of $3.85, and place the second-highest number of orders (18.6K). 

#### Packet Size by Customer Segment:

- **175g** is the **most popular packet size** across every single segment. Older Singles/Couples lead with **26,042 units**, followed by **Older Families (23,806) and Retirees (23,556)**. 

- Very small packs (70g, 90g, 125g) have low performance across all groups — CrunchCo shoppers generally prefer mid-size bags over single-serve options.
  
<p align = 'center'>
  <img width="837" height="507" alt="image" src="https://github.com/user-attachments/assets/ffbd33b7-227b-4401-a19c-ed07292b9f60" />
</p>

### Deep Dive - Mainstream Young Singles/Couples:

- **Mainstream Young Singles/Couples** stands out as the best target for CrunchCo. They have a large customer base, they pay more per bag, and they shop on impulse. 

- Two charts show an affinity score. A score above 1.0 means this group buys that brand more than the average shopper. Below 1.0 means they buy it less. 

- **Mainstream Young Singles/Couples** are **23% more likely to purchase Tyrrell's chips** compared to the rest of the population, and **56% less likely to purchase Burger**. 

- They prefer to buy a **bigger bag (270g)**, which means they are buying chips for a social occasion - movie nights, having friends over. **Twisties** is the only brand offering their **270g** preference, and this may reflect a higher likelihood of purchasing Twisties. 
<p align = 'center'>
  <img width="1200" height="700" alt="image" src="https://github.com/user-attachments/assets/03513964-0ed4-48f4-a593-5343139608f0" />
</p>
<p align = 'center'>
  <img width="1200" height="700" alt="image" src="https://github.com/user-attachments/assets/3d50eb33-7d19-419f-9ede-846507e2c6d7" /> 
</p>

## Recommendation
- The historical sales trend shows a **10-day spike before Christmas**. **The company should plan this for with festive multipacks, special displays, and loyalty card deals timed to that period.**
  
- The company is heavily reliant on Kettle, which outperformed the bottom 10 brands combined. This represents a significant risk that the company may face. The company's revenue and customer loyalty can decline quickly due to negative publicity such as product defects, scandals, and competitive disruption. So, diversifying the product portfolio is crucial. **Actively investing in the second tier, particularly Doritos, Smiths, and Pringles, which contribute 34% in total revenue, would allow balancing revenue without abandoning what already performs.**

- Burger, Sunsites, and a few other small brands have very low performance in sales. **Before discontinuing them, try bundling them with popular brand products or running flash sales to clear stock.**

- Mainstream Young Singles/Couples are 23% more likely to grab Tyrrels and 27% to buy Twisties 270g, over Kettle and other brands. **Putting these where young shoppers will see them. Moving Twisties 270g, Tyrrells with smaller packs of chips to end-of-aisle displays or near checkouts in stores will catch them at the moment they are most likely to make an impulse buy.**

- Older Families buy around 8 - 9 bags per visit. **A simple deal like "buy 3, get 1 free" would make their big spend even bigger without needing to attract new customers.**

- CrunchCo has purchase history on over 72,000 customers. **Focus on sending personalized deals to targeted groups, such as alerting a Kettle-loving Retirees about a Kellte promotion. That is a low-cost way to bring people back more often and grow how much they spend each visit.**

























