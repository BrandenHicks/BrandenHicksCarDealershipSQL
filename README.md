Overview: 
This project is designed to create a comprehensive database system for a car dealership. It includes SQL scripts for database creation, various operations, and an Entity-Relationship diagram. The system manages customer information, employee details, vehicle inventory, sales transactions, and more.



Tables: 

customer: Stores information about the dealership's customers.

employee: Contains details about the employees working at the dealership.

vehicle: Records the inventory of vehicles available at the dealership.

sale: Logs the sales transactions, linking customers to the vehicles they purchase.

make: Lists the makes of vehicles.

model: Details the models of vehicles.

color: Specifies the colors of vehicles.

type: Describes the types of vehicles (e.g., sedan, SUV).

citystate: Stores the city and state information linked by ZIP code.

cylinders: Lists the types of engine cylinders used in vehicles.


Views: 

customerview: A temporary view structure for displaying customer details.

saleview: Combines customer, employee, and vehicle information to provide a comprehensive view of sales transactions.


Prerequisites:

MySQL Server

MySQL Workbench


Steps to Setup the Database: 

1. Install MySQL Server and MySQL Workbench: Ensure MySQL is installed and running on your system. Install MySQL Workbench for managing the database visually.

2. Load the ER Diagram:
   Open "dealershipDiagram.mwb" in MySQL Workbench.
   Review the diagram to understand the database structure.

3. Create the Database:
   Execute the SQL script "dealershipCode.sql" in MySQL Workbench or via command line to create and populate the necessary tables.

5. Additional SQL Operations:
   Run "dealearshipScript.sql" for additional database operations and modifications.

