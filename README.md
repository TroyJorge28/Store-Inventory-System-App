 Store Inventory Management System

 Purpose of the Application

 General Purpose  

The Store Inventory Management System is designed to streamline and automate the management of inventory in a retail or wholesale environment. It eliminates the need for manual record-keeping, reduces errors, and provides a digital solution for tracking product stock levels, pricing, and sales.

 Specific Purpose
  
This application specifically allows users to:
- Store details about various products.
- View, add, delete, and update products in the inventory.
- Make and record sales transactions.
- Keep track of remaining stock quantities and total sales revenue.
- Persist inventory data between sessions using text file storage.

It is built with C++ using object-oriented principles and a GUI developed with Qt Creator, offering a simple and interactive way for users to manage their store inventory efficiently.

 Features

 View Inventory
- Displays a table of all products currently in the inventory.
- Shows details such as Product ID, Name, Category, Price, Quantity, and Total Value.

 Add Product
- Allows the user to enter details for a new product including ID, name, category, price, and quantity.
- Automatically calculates and updates the total inventory value.

 Delete Product
- Enables the user to remove a product from the inventory by entering its Product ID.
- Ensures that only valid products are deleted with confirmation.

 Update Product
- Allows the user to update product details such as name, price, quantity, or category.
- Maintains data accuracy by modifying records directly in the inventory.

 Make Sale
- Lets the user enter the Product ID and quantity sold.
- Automatically updates the remaining stock and calculates the total sale price.
- Adds the sale to a cumulative sales record to monitor overall revenue.

 View Total Sales
- Shows the total revenue generated from all recorded sales in the session.
- Gives an overview of the store's performance.

 File Storage

- All inventory data is saved in a text file (inventory.txt) and loaded automatically when the app starts.
- Ensures data persistence between sessions without needing a database.

 Usage Instructions

1. Launch the Application
   - Download the ZIP folder and un-ZIP it so as to access it's content
   - Open the folder and double click STS
   - Double-click on the StoreInventorySystem.exe file 
   - The main window of the application will open.

2. *Navigating the Interface*  
   - Use the buttons in the main window to choose an action:
     - View Inventory to see current stock.
     - Add Product to register a new item.
     - Delete Product to remove an existing item.
     - Update Product to change details of an existing item.
     - Make Sale to record a product sale and adjust stock.
     - View Total Sales to see the total revenue from sales.

3. Exiting the App
   - Simply close the window. Your data is automatically saved to inventory.txt.
    
   Requirements
   -This project use Qt for its graphical user interface so to run the codes you must have 
 Qt Creator installed

 Download the App

> For users who just want to run the app without compiling anything:

- [Click here to download the application](https://github.com/TroyJorge28/Store-Inventory-System-App)
- Extract the zip file.
- Run the .exe file inside.
