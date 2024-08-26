# Real Estate Data Analysis: Insights into Singapore Housing Resale Market

Accurate property valuation is essential in the real estate industry for informed decision-making. Property owners, investors, and professionals depend on precise valuation estimates to determine fair market prices, negotiate deals, and evaluate investment opportunities.

## Table of Contents
- [Data Description](#Data-Description)
- [Overview](#Overview)
- [Storey range & Flat type](#Storey-range)
- [Permits & construction value - Sylvia Broadbent](#Permits_construction)
- [First home owners grant - Lauren Prins](#First_home)
- [Conclusion](#Conclusion)
- [Limitations of the study/ Difficulties experienced](#Limitations)
- [If we had more time](#more_time)

## Data Description <a name = "Data-Description"></a>
► <b>Flat model </b>: (String) The model or type of the residential flat, which indicates the layout and design. <br>
► <b>Flat type </b>: (String) The type of the residential flat, such as 1-room, 2-room, 3-room, etc. <br>
► <b>Remaining lease years </b>: (Int)The remaining lease period of the residential flat in years. It starts at 99 years upon commencement of lease. <br>
► <b>Resale price  </b>:(Int) The price at which the residential flat was resold. <br>
► <b>Story range </b>: (String) The range of storeys where the residential flat is located in the building. <br>
► <b>Town </b>: (String) The town or area where the residential flat is situated. <br>
► <b>Town lat </b>: (Decimal) The latitude coordinates of the town where the residential flat is situated. <br>
► <b>Town lon </b>: (Decimal) The longitude coordinates of the town where the residential flat is situated. <br>

## Overview <a name = "Overview"></a>

Over the years, various factors have influenced the resale prices of apartments, including flat size, remaining lease, location, and storey range. These factors, along with market trends, evolve over time, driven by elements such as economic growth, the introduction of new amenities, or improved transportation options like new MRT lines. We will dive deeper into each points explaining how each factors affects the pricing.


![Real Estate Overview](https://github.com/user-attachments/assets/28b06b60-dfe9-4b02-8f33-add59b4b2029)
![Insight](https://github.com/user-attachments/assets/3dc2b6ac-17cb-4117-9681-ec235e7beac0)



## Storey range & Flat type <a name = "Storey-range"></a>

![storey range 1](https://github.com/user-attachments/assets/d5d8f88e-56af-491a-9ef7-3220b20ba80d)

This chart shows that the average resale price and floor area of flats vary based on storey range and flat type. Flats located in the mid-storey ranges tend to have higher resale prices, with 5-room, executive, and multi-generation flats being the most valuable. The average floor area of flats tends to be larger in the mid-storey ranges and decreases in the higher storeys. Overall, mid-storey flats, particularly those with more rooms, are more desirable due to their combination of higher resale values and larger living spaces.

![storey range 2](https://github.com/user-attachments/assets/93ceb1e9-b407-4a03-963f-b8dcaab90015)

The chart on the left indicates that multi-generation flats have the highest average resale prices, followed by executive and 5-room flats, with 1-room flats having the lowest resale prices, supporting the previous chart. In contrast, the chart on the right reveals that 4-room flats make up 40% of the total resale market, while multi-generation flats account for less than 1%, and executive flats represent only 11%. This suggests that the market is more concentrated in the mid-price range, with a higher volume of sales occurring for 4-room flats.


