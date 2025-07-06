# Amazon-Product-Review-Analysis-Digital-Skillup-Africa--Incubator-Hub-Project-
Developed at DSA Incubator, this project leveraged Ms Excel power query tables, slicers and interactive dashboards to analyze Amazon product reviews, track discounts, and monitor pricing trends. The solution delivers actionable  insights into product performance, category dynamics, customer engagement, and revenue potential.

## Company Overview
__Client__: RetailTech Insights

__Industry__: E-commerce Analytics

__Job Description__: Junior Data Analyst

__Tools Applied__: Microsoft Excel (Power Query Pivot Tables, Charts, Conditional Formatting, Slicers, Text Box)

## Dataset Description
- __Product Details__: Name, Category, Price, Discount, Ratings
- __Total Record__: 1,456 rows, each representating a unique product
- __Total Field__: 16 Columns
- __Customer Engagement__: User reviews, Titles, and Content
- __Data Source__: Amazon product pages


![Amazon Dashboard](https://github.com/user-attachments/assets/cfd664f0-9266-48c8-9b2b-8ae82e5fd391)


## Analysis Tasks and Solutions:
- 1. What is the average discount percentage by product category?
    
  ![Count of Product](https://github.com/user-attachments/assets/c7963a83-00e1-4858-a763-c5d72a63f5d5)

 
   
     __Answer:__ 47% as shown in text box on the dashboard
     
   
     __*Application*:__ High Discount as a conditional column where discount percentage is greater than or 0.5
     
     __*Observation*:__ Computers & Accessories and Electronics categories offer the highest average discounts, likely to drive sales volume.  


- 2. How many products are listed under each category?
 
     ![Count of Product](https://github.com/user-attachments/assets/180e8632-10d7-410e-8431-474a9d53520e)

 
      __Answer:__ 1,348 as shown in text box on the dashboard
     
     __*Application*:__ Split column by leftmost delimeter, removed duplicates
     
     __*Observation*:__ Electronics, Electronics, Computers & Accessories dominate the product listings

- 3. What is the total number of reviews per category?
 
      __Answer:__ 23,801,431

     __*Tool*:__ Ms Excel Power Query
     
     __*Application*:__ Summed up rating count by category on pivot table
     
     __*Observation*:__ Electronics attract the most customer feedback, indicating higher sales or engagement.  
- 4. Which products have the highest average ratings?
 
     __Answer:__ Top 3 ratings are 5,4.8, 4.0, with Syncwire and Amazon topping the list, as shown in a bar chart
     
     __*Tool*:__ Ms Excel Power Query
     
     __*Application*:__ 
     
     __*Observation*:__ High-rated products often have strong brand trust 
- 5. What is the average actual price vs the discounted price by category?
 
      __Answer:__
     
     ![Actual vs Discount Prices](https://github.com/user-attachments/assets/57da443d-186b-47d1-aa6c-1c8c638fda8a) ![Actual-Discount Prices](https://github.com/user-attachments/assets/867a9874-2bf1-4d79-9957-b2ea12dd6f1a)

     
     __*Tool*:__ Ms Excel Power Query
     
     __*Application*:__ I added Disocunt Band as conditional column, values from 0.1%-0.9% is less than or equal to output of 0%-90% in 9 clauses
     
     __*Observation*:__ *: Electronics have higher absolute discounts, while Computers & Accessories have deeper percentage discounts.  
- 6. Which products have the highest number of reviews?
 
     __Answer:__ Aamazon Basics, Boat Bassheads, Redmi,JBL
     
     __*Application*:__ Low Review as conditional column where rating count is less 1000 to show high review - shown in bar chart
     
     __*Observation*:__ Affordable, high-utility products (earphones, cables) generate the most reviews.
- 7. How many products have a discount of 50% or more?

     __Answer:__ 660
     
     __*Tool*:__ Ms Excel Power Query
     
     __*Application*:__ Added a conditional column where discount percentage is greater than or equal to 0.5 as yes
     
     __*Observation*:__Heavy discounts are common, likely to compete in crowded categories.  
 
- 8.  What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)?

      __Answer:__
      ![Rating Distribution](https://github.com/user-attachments/assets/3ae8dad4-0dd5-484a-824f-e3734c66eb1e)
![Product Rating](https://github.com/user-attachments/assets/b65d31c5-11e0-4dbe-bf1c-806028686ee8)
     
      __*Observation*:__ *: Most products maintain good ratings (4+), indicating satisfactory quality.  
- 9. What is the total potential revenue (actual_price × rating_count) by category?

![Potential Revenue](https://github.com/user-attachments/assets/4e971bb9-cadd-4734-8b9c-f65283c4c4e1)

 
       __*Observation*:__ Electronics drive the most revenue potential, despite fewer products than Computers & Accessories.  
- 10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)?

![Unique Products](https://github.com/user-attachments/assets/75c59afc-49ad-4d4f-9675-42ae80e29d63)


      
       __*Observation*:__ Majority of products are priced above $500, targeting mid-range buyers.  
- 11. How does the rating relate to the level of discount?
 
     ![Rating-Discount](https://github.com/user-attachments/assets/0d30afcd-9f6e-46da-ae26-b1a8f734e51a)

     
       __*Observation*:__ Products with lower discounts tend to have slightly higher ratings, possibly due to perceived quality.  
- 12. How many products have fewer than 1,000 reviews?
      ![Less than 1k Reviews](https://github.com/user-attachments/assets/debccae3-bcf5-4f0f-b2b3-b742e94e9404)

 
       __Answer:__ 150 products 
     
       __*Tool*:__ Ms Excel Power Query
     
       __*Application*:__ 
     
       __*Observation*:__
- 13. Which categories have products with the highest discounts?
 
       __Answer:__
      
      Musical Instruments (60% avg. discount)  

      Computers & Accessories (55%). 
  
      Electronics (50%).  
     
       __*Observation*:__ Non-essential categories (e.g., Musical Instruments) use deeper discounts to attract buyers.
- 14. Identify the top 5 products in terms of rating and number of reviews combined.

![Top 5 Products](https://github.com/user-attachments/assets/eb6e57d3-b3e0-4b30-9c7e-22f69449b5e5)


# About Me

## Benita Oghojafor Mahmud - I am new to the IT world, and I am excited to showcase my first project. 

_Email_: mahmudbenita@gmail.com

_Phone_: __07038406172__
