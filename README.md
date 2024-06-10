# Power-BI-Supersotores-Sales-Dashboard
## Introduction
A Retail Company has stores around the word. Senior Manager wants to have a overview about bussiness for expand strategy and choosing key products. In this project, I apply Design Thinking framework to build a dashboard by Power BI. I will carry out analysis that involve 3 step: Design Thinking, Data Modeling and Visualization.
## Dataset
This Dataset record sales of branches accross the word. It contains 3 tables:
- Ordes: Fact table.
- People: Salesperson information.
- Return: Returned orders.
### Orders Table
|Field|Datatype|
|:----|-------:|
|Order ID|varchar|
|Order Date|date| 
|Ship Date|date|
|Ship Mode|varchar|
|Customer ID|varchar|
|Customer Name|varchar|
|Segment|varchar|
|City|varchar|
|State|varchar|
|Country|varchar|
|Postal Code|numeric|
|Market|varchar|
|Region|varchar|
|Product ID|varchar|
|Category|varchar|
|Sub-Category|varchar|
|Product Name|varchar|
|Sales|varchar|
|Quantity|numeric|
|Discount|numeric|
|Profit|numeric|
|Shipping Cost|numeric|
|Order Priority|varchar|

### People Table
|Field|Datatype|
|:----|-------:|
|Person|varchar|
|Region|varchar|

### Return Table
|Field|Datatype|
|:----|-------:|
|Returned|varchar|
|Order ID|varchar|
|Market|varchar|

## Design Thinking
![Design Thinking Framework](https://github.com/ducpham131/Power-BI-Supersotores-Sales-Dashboard/assets/169105426/8ae7d84c-8199-434a-a5ab-2d124eb4ecb5)


## Data Modeling
I create a dimension table using Power Query. This way, I can manage key dimensions more effectively and improve performance.

<img src="https://github.com/ducpham131/Power-BI-Supersotores-Sales-Dashboard/assets/169105426/94c87618-77ac-4dd7-a269-78240bada272" alt="..." width="700" />

## Visualization

![Superstores Sales Dashboard](https://github.com/ducpham131/Power-BI-Supersotores-Sales-Dashboard/assets/169105426/47676119-9187-4b2d-b30e-ce7289baae70)

## Insights
- The number of orders tends to increase in the last quarters of the year, while **ROS** (Return on Sales) tends to increase in the first quarters of the year.
- **Consumer** customers account for the highest proportion of revenue **(51.63%)**.
- The **Priority** level of orders is mainly at the **Medium** level **(57.76%)**, followed by the **High** level **(30.4%)**.
- The **Market** with the highest revenue is **APAC (3.32M)**, but it also has the highest average **Shipping cost** per product **(35.19)**.
- The **US** is the country with the highest revenue **(2.3M)**, far ahead of the second-ranked country, **Australia (0.89M)**, and the third-ranked country, **France (0.8M)**.
- The average shipping time of **Shipping Modes** does not vary much between markets.
- The **Technology Category** accounts for high **revenue (4.51M)** across markets and is also the Category with the highest **profit (623K)**.
- **Copiers** and **Phones** is the **Sub-Category** with the highest revenue and profit, while **Tables** is an ineffective product that does not generate profit.

## Recommendations
- Ensure sufficient inventory to meet the strong increase in demand at the end of the year, avoiding stock-out situations.
- In markets with high sales, continue to expand and develop in countries like the **US**, **Australia**, **China**, **France**, and **Germany**.
- In inefficient markets such as **Canada** and **Africa**, consider whether to continue maintaining business to gain market share or withdraw to focus on developing other markets.
- Increase competitiveness by reducing **delivery times** or lowering **shipping costs**.
- **Copiers** and **Phones** can be chosen as strategic products due to their high revenue and profits. Consider stopping the sale of **Tables** products due to their losses.
