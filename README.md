# Duplicate Products Merging
Transformation to clean up duplicate products into a single record of data

**Problem Statement**
The given SQL file is a database that contains dummy data of our products. We have around 350k products on that sql file. There are many duplicate products from different suppliers from that collection. We need to merge those duplicate products into one single unique product, to remove customer confusion and improve the sales metrics.

**Similar Product Indicators**
- Product ID (available in product tags)
- Gender
- Product Category

**Goals**
1. Create python script to generate product merge suggestions in daily basis, insert a data to product_duplicates and product_duplicate_details table
2. Create a query to retrieve the list of merge suggestions
