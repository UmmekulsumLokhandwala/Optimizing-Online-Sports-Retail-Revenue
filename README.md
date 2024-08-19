# Optimizing Online Sports Retail Revenue

![image](https://github.com/user-attachments/assets/5a9dec4a-2182-4587-be85-beedb4bfca75)

**Project Overview**

This project demonstrates how to use SQL for data analysis to optimize revenue for an online sports retail business. It involves analyzing sales, customer reviews, and traffic data to identify opportunities for revenue growth and cost reduction. The goal is to leverage SQL techniques to enhance decision-making and drive business improvements. 

**Database Overview**

*Link* : [Click Here](https://www.kaggle.com/code/nickleejh/optimizing-online-sports-retail-revenue-using-sql/input)

The data has five supporting tables that include the following: 

**brands_v2**: This table has two variables - product_id (Unique number for the product) and brand (brand of the product). 

**finance**: This table has five variables - product_id (Unique number for the product), listing_price (The price listed for the product), sale_price (The price of the product when on sale), discount (Discount assigned to the product), and revenue (Amount of revenue generated in USD).

**reviews_v2**: This table has three variables - product_id (Unique number for the product), rating (Product rating from 1.0 to 5.0), and reviews (Number of reviews for the product). 

**traffic_v3**: This table has two variables - product_id (Unique number for the product), and last_visited (Date and time when the product was last visited on the website). 

**info_v2**: This table has three variables - product_id (Unique number for the product), product_name (The name of the particular product), and description (Description of the product)

**Objectives**

- Counting the missing entities in the dataset.
- Finding out the price difference between the two brands. (Nike VS Adidas)
- Categorizing/ Labeling the price range for the brands in terms of 'Budget', 'Average', 'Expensive', and 'Elite'.
- Average discount offered by the specific brand.
- Correlation between revenue and reviews.
- Ratings and reviews by product description length.
- Reviews by month and brand.

**Applications Used** 

SQL Server Extension in Visual Studio Code as operating on iOS device. 

**Results**

*Counting the missing entities in the dataset.*


<img width="627" alt="Screenshot 2024-08-19 at 3 38 57 PM" src="https://github.com/user-attachments/assets/0d0f4706-626f-4bc4-b687-9cbe53a8c04b">


*Finding out the price difference between the two brands. (Nike VS Adidas)*


<img width="392" alt="Screenshot 2024-08-19 at 3 47 31 PM" src="https://github.com/user-attachments/assets/194a81a1-542b-4865-94b6-831f214ea7f6">


*Categorizing/ Labeling the price range for the brands in terms of 'Budget', 'Average', 'Expensive', and 'Elite'.*

<img width="517" alt="Screenshot 2024-08-19 at 3 53 48 PM" src="https://github.com/user-attachments/assets/16193d82-d691-4ea6-8bd9-c8d134086cd9">

*Average discount offered by the specific brand.*

<img width="331" alt="Screenshot 2024-08-19 at 3 55 33 PM" src="https://github.com/user-attachments/assets/e093d208-43b1-4134-9a6f-53aad9eee4b2">

*Correlation between revenue and reviews.*


<img width="218" alt="Screenshot 2024-08-19 at 3 56 42 PM" src="https://github.com/user-attachments/assets/2584e4bb-f2d1-454e-b948-47706ae23bd1">

*Ratings and reviews by product description length.*

<img width="300" alt="Screenshot 2024-08-19 at 3 58 05 PM" src="https://github.com/user-attachments/assets/2f4d56ec-aedf-4ae0-9219-2ed0990f9167">

*Reviews by month and brand.*

<img width="396" alt="Screenshot 2024-08-19 at 3 58 59 PM" src="https://github.com/user-attachments/assets/3587d7af-0e4c-4f6c-bf9c-47f149a4aab2">

(*Please view the source code in the repository*)









