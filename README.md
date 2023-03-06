# Super Store Segmentation and Discount Analysis
Author's : Aliriza Hamonangan Matondang
## Purpose
- Create customer segmentation to understand the customer profile
- Do discount analysis by the segmentation of the customer
- Create the recommendation of discount promotion
- Issue identification and the weakness of Super Store to increase the Profit
## Data Information
The dataset is from 2014 - 2017, contains 21 Features, and 9994 rows

- Row ID => Unique ID for each row.
- Order ID => Unique Order ID for each Customer.
- Order Date => Order Date of the product.
- Ship Date => Shipping Date of the Product.
- Ship Mode=> Shipping Mode specified by the Customer.
- Customer ID => Unique ID to identify each Customer.
- Customer Name => Name of the Customer.
- Segment => The segment where the Customer belongs.
- Country => Country of residence of the Customer.
- City => City of residence of of the Customer.
- State => State of residence of the Customer.
- Postal Code => Postal Code of every Customer.
- Region => Region where the Customer belong.
- Product ID => Unique ID of the Product.
- Category => Category of the product ordered.
- Sub-Category => Sub-Category of the product ordered.
- Product Name => Name of the Product
- Sales => Sales of the Product.
- Quantity => Quantity of the Product.
- Discount => Discount provided.
- Profit => Profit/Loss incurred.

## Steps
- Data Cleaning 
- Change some features data types & drop features
- Feature Engineering
- Exploratory Data Analysis
- RFM Segmentation
- K-Means Cluster
- Evaluation

## Conclusion
- The budget of promotion at Super Store is quite good in range 10 - 20% from profit, but it can be more efficient with providing promotion based on customer target to increase the profit and reduce the promotion budget
- The difference between GMV and Profit values is 2010803.8386 which is  very high. So it is necessary to evaluate the promotion and the operational costs 
- The Loyalty Program is needed in order to be able to provide promotion according to target customers and provide maximum profit
- Central region is the region where is the weakness of the Super Store based on profit, because the promotion that has given is quite high, but the GMV generated is also high
- The best discount value are 10-20 % based on profit and customers profil 
- Super Store needs to increase the promotion on bottom products to  introduce the bottom products and increase orders for these products for increasing the profit 

## Recommendation
- Super Store needs to create Loyalty program based on customer segmentation or Customer Lifetime Value so the promotion will given to the target customers
- Super Store needs to re-evaluate the discount promotion value based on product prices to maximize the profit and the customers would feel they are getting the best price Ex: high prices low discounts or low prices high discounts but adjust with the profit to avoid the high loss profit
- The discounts price on product display, could be adjusted to the nominal product discounts that will be given based on customer segments (Ex : The discount Price is 5% at the display products, but we give them 5% after they pay the bill so the total discount is 10%)
- Super Store could create voucher discount that send to email, WhatsApp, etc before they go shopping, in order to attract customers to shop by loyalty program
- It is necessary to do evaluation on operational perspective to find out more about the weaknesses of the Super Store and the reason of high loss profit
- Super Store needs to re-evaluate promotion and operational costs at the centre region to increase the profit, because it has been running for 4 years but the profit generated is not optimal
- Diverting promotion budget from top product  to bottom 9 products to introduce the bottom 9 products and increase sales of these products, or re-evaluate the bottom 9 products, whether they should be abolished or keep the products
- Super Stores could choose K-Means Cluster or RFM Segmentation to segment the customers, because the results of K-Means Cluster and RFM Segmentation are similar, but for RFM Segmentation it has more detailed groups because there are 8 segments by RFM Segmentation
