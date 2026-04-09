Inventory Management System Prototype

This Python program is a simple inventory tracking system. It allows users to:

Add items to the inventory
Automatically generate unique item IDs
Calculate total value for each item

This prototype demonstrates basic Python concepts such as variables, functions, input/output, and simple calculations.

Features

Add Inventory Item

Users can enter item name, quantity, and price per item. Each new item automatically gets a unique itemID.
Calculate Total Value:
The total price for each item is calculated automatically as quantity × price.

Display Item Details:
The program prints the item’s name, ID, quantity, price, and total value.
Update Inventory (Partial Implementation):
A function is included to update quantity and price by entering the item ID (needs minor adjustments for full functionality).

How It Works
itemID is a global variable that starts at 1000 and increments automatically whenever a new item is added.
calculate_total_value(price, quantity) computes the total price.
add_inventory_id():
Prompts the user for item name, quantity, and price
Generates a new item ID
Returns all item information
update_Inventory() (not fully implemented yet):
Prompts the user for item ID
Allows updating quantity and price
Example Usage

Add a new item
totalPrice, itemName, quantity, price = add_inventory_id()

Display item details
print(f"Item : {itemName}")
print(f"Item Id: {itemID}")
print(f"Quantity: {quantity}")
print(f"Price: ${price}")
print(f"Total Price: ${totalPrice}")

Sample Output:

Enter the item name: Pen
Enter the quantity: 10
Enter the price per item: $2
Item : Pen
Item Id: 1001
Quantity: 10
Price: $2
Total Price: $20
Getting Started
Make sure you have Python 3 installed.
Copy the code into a .py file, e.g., inventory_system.py.
Run the program:
python inventory_system.py
Follow the prompts to add items.
Notes
The program currently handles one item at a time.
update_Inventory() can be extended to fully update multiple items by storing all items in a list.
Designed for learning functions, global variables, and user input in Python.
