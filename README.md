
# Prachi's Store Management Software

This is a Store Management System web application built using Python Flask, JavaScript, and SQL database.

## Description

Prachi's Store Management System is a web-based application that enables store owners or managers to efficiently manage their store's inventory, track orders, and perform various administrative tasks. The application provides an intuitive user interface for easy navigation and interaction.
---

## Backend

### Overview:

The backend of Prachi's Store Management Software is built using the Flask framework in Python. It interfaces with a MySQL database to manage products and orders for a store.

### Main Files:

1. **server.py**: Initializes and runs the Flask server, defining various endpoints for API interactions.
2. **manage_functions.py**: Contains functions for product and order management.
3. **sql_connect.py**: Manages the connection to the MySQL database.

### API Endpoints:

1. **GET `/getProducts`**: Fetches all products.
2. **POST `/insertProduct`**: Inserts a new product.
3. **POST `/deleteProduct`**: Deletes a product.
4. **GET & POST `/getAllOrders`**: Retrieves all orders.
5. **POST `/insertOrder`**: Inserts a new order.
6. **GET & POST `/orderDetails`**: Retrieves details of a specific order.
7. **GET `/getUOM`**: Retrieves units of measurement.

### Management Functions:

1. **Products**:
   - `get_all_products()`: Fetches all products.
   - `insert_new_product()`: Inserts a new product.
   - `delete_product()`: Deletes a product based on its ID.
   - `update_a_product()`: Updates a product's details.

2. **Orders**:
   - `insert_order()`: Inserts a new order.
   - `get_all_order_details()`: Retrieves detailed information about all orders.
   - `get_order_details()`: Fetches details of a specific order.
   - `get_all_orders()`: Retrieves a list of all orders.

3. **Utility**:
   - `get_uoms()`: Retrieves a list of units of measurement.

---

## Frontend

The frontend of Prachi's Store Management Software is built using HTML, CSS, and JavaScript. The main components include:

1. **index.html**: The main landing or homepage of the web app.
2. **order.html**: A page dedicated to handling and viewing orders.
3. **order_details.html**: Provides detailed information about a specific order.
4. **manage-product.html**: A page for managing products, allowing for CRUD operations.

### Directories:

1. **images**: Contains image assets used in the web app.
2. **js**: Contains JavaScript files that provide interactivity and dynamic functionalities for the web app.
3. **css**: Contains stylesheets to define the look and feel of the web app.

### Installation

1. Clone the repository: git clone https://github.com/iprachigoyal/store_management.git
2. Navigate to the project directory
3. Install the required dependencies: pip install -r requirements.txt
4. Set up the SQL database.
EER Diagram is attached to understand the type of database
<img width="538" alt="sql" src="https://github.com/iprachigoyal/store_management/assets/106303603/3818b2c9-5251-4d81-b99b-6c8d1ada72d0">

6. Run the application, server.py
7. Access the web application in your browser: (use path of ./grocery_app/ui/index.html as browser url)
---

This app is made by Prachi Goyal in 2023.
