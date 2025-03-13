# Online-food-ordering-system

1. INTRODUCTION
The online food ordering system is designed to manage customers, restaurants, food items, orders, and payments efficiently. SQL is used to create, manage, and query the relational database for this system.

2. DATABASE DESIGN
The database consists of the following tables:
Customers Table:
Columns: CustomerID (Primary Key), Name, Email, Phone, Address.
Purpose: Stores customer details.
Restaurants Table:
Columns: RestaurantID (Primary Key), Name, CuisineType, Address, Phone.
Purpose: Stores restaurant information.
FoodItems Table:
Columns: FoodID (Primary Key), RestaurantID (Foreign Key), Name, Category, Price.
Purpose: Stores menu items for each restaurant.
Orders Table:
Columns: OrderID (Primary Key), CustomerID (Foreign Key), OrderDate, TotalAmount, OrderStatus.
Purpose: Stores order details.
OrderDetails Table:
Columns: OrderDetailID (Primary Key), OrderID (Foreign Key), FoodID (Foreign Key), Quantity, Price.
Purpose: Stores details of each order.
Payments Table:
Columns: PaymentID (Primary Key), OrderID (Foreign Key), PaymentDate, Amount, PaymentMethod.
Purpose: Manages payment information.

FEATURES AND FUNCTIONALITY
1.Customer Management:
*Add, update, and delete customer details.
*Retrieve customer order history.
2.Restaurant Management:
*Add and manage restaurant details.
8Retrieve menu items for each restaurant.
3.Order Management:
*Place, update, and cancel orders.
*Track order status.
4.Payment Management:
*Record and retrieve payment details.
*Generate revenue reports.
5. Best Practices
*Use Primary Keys for unique identification of records.
*Use Foreign Keys to establish relationships between tables.
*Normalize the database to reduce redundancy.
*Use Indexes for faster query performance.
