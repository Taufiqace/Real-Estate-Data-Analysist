# Real Estate Data Analysis: Insights into Singapore Housing Resale Market

Accurate property valuation is essential in the real estate industry for informed decision-making. Property owners, investors, and professionals depend on precise valuation estimates to determine fair market prices, negotiate deals, and evaluate investment opportunities.

## Table of Contents
- [Data Description](#data-description)
- [Overview](#Overview)
- [Storey range & Flat type](#storey-range-&-flat-type)
- [Town location](#town-location)
- [Resale price trend & lease impact](#Resale-price-trend-&-lease-impact)
- [Conclusion](#Conclusion)
- [Limitations of the study/ Difficulties experienced](#Limitations)
- [If we had more time](#more_time)

## <a name = "data-description"></a>Data Description 
► <b>Flat model </b>: (String) The model or type of the residential flat, which indicates the layout and design. <br>
► <b>Flat type </b>: (String) The type of the residential flat, such as 1-room, 2-room, 3-room, etc. <br>
► <b>Remaining lease years </b>: (Int)The remaining lease period of the residential flat in years. It starts at 99 years upon commencement of lease. <br>
► <b>Resale price  </b>:(Int) The price at which the residential flat was resold. <br>
► <b>Story range </b>: (String) The range of storeys where the residential flat is located in the building. <br>
► <b>Town </b>: (String) The town or area where the residential flat is situated. <br>
► <b>Town lat </b>: (Decimal) The latitude coordinates of the town where the residential flat is situated. <br>
► <b>Town lon </b>: (Decimal) The longitude coordinates of the town where the residential flat is situated. <br>

## Overview <a name ="Overview"></a>

Over the years, various factors have influenced the resale prices of apartments, including flat size, remaining lease, location, and storey range. These factors, along with market trends, evolve over time, driven by elements such as economic growth, the introduction of new amenities, or improved transportation options like new MRT lines. Using data from 2015 to 2019, we will dive deeper into each points explaining how each factors affects the resale pricing.


![Real Estate Overview](https://github.com/user-attachments/assets/28b06b60-dfe9-4b02-8f33-add59b4b2029)
![Insight](https://github.com/user-attachments/assets/3dc2b6ac-17cb-4117-9681-ec235e7beac0)



## <a name ="storey-range-&-flat-type"></a>Storey range & Flat type 

![storey range 1](https://github.com/user-attachments/assets/d5d8f88e-56af-491a-9ef7-3220b20ba80d)

This chart shows that the average resale price and floor area of flats vary based on storey range and flat type. Flats located in the mid-storey ranges tend to have higher resale prices, with 5-room, executive, and multi-generation flats being the most valuable. The average floor area of flats tends to be larger in the mid-storey ranges and decreases in the higher storeys. Overall, mid-storey flats, particularly those with more rooms, are more desirable due to their combination of higher resale values and larger living spaces.

![storey range 2](https://github.com/user-attachments/assets/93ceb1e9-b407-4a03-963f-b8dcaab90015)

The chart on the left indicates that multi-generation flats have the highest average resale prices, followed by executive and 5-room flats, with 1-room flats having the lowest resale prices, supporting the previous chart. In contrast, the chart on the right reveals that 4-room flats make up 40% of the total resale market, while multi-generation flats account for less than 1%, and executive flats represent only 11%. This suggests that the market is more concentrated in the mid-price range, with a higher volume of sales occurring for 4-room flats.

## <a name ="town-location"></a>Town location 

![Town](https://github.com/user-attachments/assets/d56b1b38-407c-437f-b393-6d5ac649d01e)

This visual data shows a variation in the housing resale market across different towns. The map shows the average resale price for flats in each town, represented by bubble sizes. Towns such as Bukit Merah, Queenstown, and Bishan have larger bubbles, indicating higher average resale prices, while towns like Jurong West, Sengkang, and Yishun have smaller bubbles, signifying lower average resale prices.

The bar chart highlights the total resale prices by town, with Sengkang, Tampines, and Jurong West showing the highest total resale values. This suggests that these towns have a higher volume of transactions, even though their average resale prices are not the highest. On the other hand, towns like Bukit Timah, Marine Parade, and Central Area have the lowest total resale prices, indicating fewer transactions. 

Overall, the data suggests that while some towns have higher average resale prices, the majority of the market activity is concentrated in areas with mid-range prices, reflecting a diverse housing market with different levels of demand and property values across Singapore.

## <a name ="Resale-price-trend-&-lease-impact"></a>Resale price trend & lease impact 

![Over the years](https://github.com/user-attachments/assets/1046f006-2f09-469a-9c48-10e35e010a82)

This charts provide a comprehensive view of the resale property market trends. The total resale prices have generally increased over this period, despite some fluctuations. A noticeable rise occurred in 2016 and 2017, followed by a slight dip in 2018 and then a sharp increase in 2019, indicating a growing market in terms of total value.

In contrast, the average resale price has remained relatively stable, with only minor fluctuations. There was a slight increase in 2018, but this was followed by a decrease in 2019. This suggests that while more properties may have been sold, or higher-value properties contributed to the total increase, the average price has not seen a significant long-term rise.

The relationship between resale price and remaining lease years reveals that properties with around 50 remaining lease years tend to have the highest average resale prices. Properties with significantly fewer lease years are less valuable, while those with too many remaining years also see a dip in average price, possibly due to a different buyer perception or market demand dynamics. 

Overall, the market shows resilience and growth in total value, while the average price remain stable and its relationship with lease years shows that longer lease is prefered.


