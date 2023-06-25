# Milestone 2 
# CST 391
## Vrijesh Patel
## Web application for CST 391

--------------------------------------
--------------------------------------

# Project Introduction 
I am planning to build an online shopping portal developed using Express.js and MySQL database, following the Model-View-Controller (MVC) architectural pattern. This application aims to provide users with a seamless and intuitive online shopping experience. With a user-friendly interface and efficient database management, customers will be able to browse a wide range of products, add them to their cart, and securely complete their transactions. The MVC pattern ensures a clear separation of concerns, enabling easy maintenance and scalability. By leveraging the power of Express.js and MySQL, we aim to create a robust and efficient platform that revolutionises the way people shop online.

-------------------------------------------------

# Functionality Requirements


1.	As a user, I want to be able to create an account so that I can personalise my experience 

2.	As a user, I want to be able to search for products by category so i can easily search for what I am looking for

3.	As a user, I want to view products in a detailed manner. Details should include price, image, description so that user can make purchasing decision accordingly

4.	 As a user, I want to be able to add products to cart and update the number of products as needed.

5.	As an admin, I want to save user information in Database.

6.	As an admin, I want to manage products 
-------------------------------------------------
# REST API Points

These are some of the REST API end points that I am considering implementing for my application.

1. User Registration :
- POST/users/registration : Create new user account
2. User Authentication:
- POST/users/login : Authentiate user credential 
3. Product Seach:
- GET/products : Retrieve all products
- GET/products/:id : Retrieve perticular product by id
- GET/products/category/:category: Retrieve by perticular category
4. Shopping Cart:
- GET/cart: : Retrieve the user's shopping cart.
- POST/cart/add : Ad a product to the shopping cart
- PUT/cart/update/:productID : Update the quantity of product in shopping cart
- Delete/cart/remove/: productID : Remove a product from shopping cart.
5. User Profile:

- GET/users/profile : Retrieve the user's profile information
- PUT/users/profile : Update the user's profile information

6. Admin Product Management:
- POST/admin/products : Add a new Product.
- PUT/admin/product/:id : Update product information
- Delete/admin/products/:id : Delete product















