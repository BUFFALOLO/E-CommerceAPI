# Module 6 - Mini-Project - E-Commerce API

**Project Requirement:** To successfully build our e-commerce application and achieve the learning objectives, we need to establish clear project requirements. These requirements outline the key features and functionalities that our application must encompass. Below, you'll find a comprehensive list of project requirements based on our learning objectives.


*Customer and CustomerAccount Management:*
Create the CRUD (Create, Read, Update, Delete) endpoints for managing Customers and their associated CustomerAccounts:
- Create Customer: Implement an endpoint to add a new customer to the database. Ensure that you capture essential customer information, including name, email, and phone number.
- Read Customer: Develop an endpoint to retrieve customer details based on their unique identifier (ID). Provide functionality to query and display customer information.
- Update Customer: Create an endpoint for updating customer details, allowing modifications to the customer's name, email, and phone number.
- Delete Customer: Implement an endpoint to delete a customer from the system based on their ID.
- Create CustomerAccount: Develop an endpoint to create a new customer account. This should include fields for a unique username and a secure password.
- Read CustomerAccount: Implement an endpoint to retrieve customer account details, including the associated customer's information.
- Update CustomerAccount: Create an endpoint for updating customer account information, including the username and password.
- Delete CustomerAccount: Develop an endpoint to delete a customer account.


*Product Catalog:*
Create the CRUD (Create, Read, Update, Delete) endpoints for managing Products:
- Create Product: Implement an endpoint to add a new product to the e-commerce database. Capture essential product details, such as the product name and price.
- Read Product: Develop an endpoint to retrieve product details based on the product's unique identifier (ID). Provide functionality to query and display product information.
- Update Product: Create an endpoint for updating product details, allowing modifications to the product name and price.
- Delete Product: Implement an endpoint to delete a product from the system based on its unique ID.
- List Products: Develop an endpoint to list all available products in the e-commerce platform. Ensure that the list provides essential product information.
- View and Manage Product Stock Levels (Bonus): Create an endpoint that allows to view and manage the stock levels of each product in the catalog. Administrators should be able to see the current stock level and make adjustments as needed.
- Restock Products When Low (Bonus): Develop an endpoint that monitors product stock levels and triggers restocking when they fall below a specified threshold. Ensure that stock replenishment is efficient and timely.


*Order Processing:*
Develop comprehensive Orders Management functionality to efficiently handle customer orders, ensuring that customers can place, track, and manage their orders seamlessly.
- Place Order: Create an endpoint for customers to place new orders, specifying the products they wish to purchase and providing essential order details. Each order should capture the order date and the associated customer.
- Retrieve Order: Implement an endpoint that allows customers to retrieve details of a specific order based on its unique identifier (ID). Provide a clear overview of the order, including the order date and associated products.
- Track Order: Develop functionality that enables customers to track the status and progress of their orders. Customers should be able to access information such as order dates and expected delivery dates.
- Manage Order History (Bonus): Create an endpoint that allows customers to access their order history, listing all previous orders placed. Each order entry should provide comprehensive information, including the order date and associated products.
- Cancel Order (Bonus): Implement an order cancellation feature, allowing customers to cancel an order if it hasn't been shipped or completed. Ensure that canceled orders are appropriately reflected in the system.
- Calculate Order Total Price (Bonus): Include an endpoint that calculates the total price of items in a specific order, considering the prices of the products included in the order. This calculation should be specific to each customer and each order, providing accurate pricing information.


*Database Integration:*
- Utilize Flask-SQLAlchemy to integrate a MySQL database into the application.
- Design and create the necessary Model to represent customers, orders, products, customer accounts, and any additional features.
- Establish relationships between tables to model the application's core functionality.
- Ensure proper database connections and interactions for data storage and retrieval.


*Data Validation and Error Handling:*
- Implement data validation mechanisms to ensure that user inputs meet specified criteria (e.g., valid email addresses, proper formatting).
- Use try, except, else, and finally blocks to handle errors gracefully and provide informative error messages to guide users.


*User Interface (Postman):*
- Develop Postman collections that categorize and group API requests according to their functionality. Separate collections for Customer Management, Product Management, Order Management, and Bonus Features should be created for clarity.
