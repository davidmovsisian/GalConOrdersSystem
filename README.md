# GalConOrdersSystem

The application is designed by using ASP.NET MVS framework.
dbo.CreateDbAndTables.sql and dbo.InsertData.sql SQL procedures create the tables in GalConOrders DB and load the test data into it.

LoginController.cs is responsiable to handle the login procedure.
OrderController.cs is responsiable for access to Orders.
UsersController.cs is responsiable for access to Users.

Each controller binded to it's views for reading the inputs and displaying the output.

The interaction with DB done by using the tables models, Order.cs, User.cs, UserRole.cs
