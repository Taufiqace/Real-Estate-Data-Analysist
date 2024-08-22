# Real Estate Data Analysis: Insights into Singapore Housing Resale Market

Accurate property valuation is essential in the real estate industry for informed decision-making. Property owners, investors, and professionals depend on precise valuation estimates to determine fair market prices, negotiate deals, and evaluate investment opportunities.

### Data Description
► <b>Flat model </b>: (String) The model or type of the residential flat, which indicates the layout and design.
► <b>Flat type </b>: (String) The type of the residential flat, such as 1-room, 2-room, 3-room, etc
► <b>Remaining lease years </b>: (Int)The remaining lease period of the residential flat in years. It starts at 99 years upon commencement of lease.
► <b>Resale_price  </b>:(Int) The price at which the residential flat was resold.
► <b>Story range </b>: (String) The range of storeys where the residential flat is located in the building.
► <b>Town </b>: (String) The town or area where the residential flat is situated
► <b>Town lat </b>: (Decimal) The latitude coordinates of the town where the residential flat is situated.
► <b>Town_lon </b>: (Decimal) The longitude coordinates of the town where the residential flat is situated.

# First
### product Clustering

we cluster the products using tf-idf technique to get each term a score based on its importance in such product
and created matrix to be applied on `K-Means Clustering algorithms`

![Word Cloud Representation for the Product clusters](imgs/word_cloud.PNG)

# Second
### Customer Clustering

We add such **product categories** through the main dataframe, such that each **Customer** got a defined **Category**
Some New Features were added to such Dataframe, such as:
  * Number of visits
  * total Cashe payed
  * Min/ Max Cashe payed 
  * Average Cashe payed

After that we Begin the Clustering with `K-Means Clustering algorithms` which ended to be `11 customer categories`

![PCA Explanied Variace](imgs/pca_plots_cum.PNG)

# Third
### final Dataframe
The final Dataframe will contains all information of each **Customer Cluster**
Dimensions (11,13) ::
  - 11 Clusters
  - 13 Feature (`cluster`,[`count`, `sum`, `Avg`, `min`,`max`], [`6 product category`])

Such Dataframe will be the Key for the followin Gerat Radar Visulization

![Radar Chart](imgs/radar_plot.PNG)

Such fabulous chart indicates how **Clusters** are more to buy from such **Category** 
* Customers of **Cluster 0** are <b style="color:violet">highly biased</b> to buy products from **0 category**
* Customers of **Cluster 1** are also impressed with **category 1** products
* Customers of **Cluster 2** more to buy products from **category 3** than any other category

# Finally
### We Do the Customer Classification

models Used [`Support Vector Machine`, `Logostic Regression`,  `k-Nearest Neighbors`, `Decision Tree`, `Random Forest`, `Gradient Boosting`, `Ada Boost`]

Which Ends with ***87.38 %*** Prediction accuracy
