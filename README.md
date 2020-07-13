# Analytics Vidhya-Janta-Hack-Demand-Forecasting

![analyticsdemand](https://user-images.githubusercontent.com/56091634/87282865-4ff8a580-c512-11ea-8af5-bade6db4e253.png)

One of the largest retail chains in the world wants to use their vast data source to build an efficient forecasting model to predict the sales for each SKU in its portfolio at its 76 different stores using historical sales data for the past 3 years on a week-on-week basis. Sales and promotional information is also available for each week - product and store wise. 

However, no other information regarding stores and products are available. Can you still forecast accurately the sales values for every such product/SKU-store combination for the next 12 weeks accurately? If yes, then dive right in!

## Data Description

record_ID - Unique ID for each week store sku combination
week - Starting Date of the week
store_id - Unique ID for each store (no numerical order to be assumed)
sku_id - Unique ID for each product (no numerical order to be assumed)
total_price - Sales Price of the product 
base_price - Base price of the product
is_featured_sku - Was part of the featured item of the week
is_display_sku - Product was on display at a prominent place at the store
units_sold - (Target) Total Units sold for that week-store-sku combination

### sample_submission.csv

record_ID - Unique ID for each week store sku combination
units_sold - Target) Total Units sold for that week-store-sku combination

## Evaluation Metric
The evaluation metric for this competition is 100*RMSLE (Root Mean Squared Log Error).

## Leaderboard Rank: 34

## Local cv: 390

## Online cv: 455
