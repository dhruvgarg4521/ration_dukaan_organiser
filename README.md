# Ration Inventory Organiser

The **Ration Inventory Organiser** is a console-based application designed to manage the inventory of a ration shop. The program allows you to add items to the inventory, update existing items, generate bills, and display the current inventory.

## Features

- **Add Item to Inventory**: Add new items with a specified rate and quantity.
- **Update Inventory**: Update the rate of an item and add new quantities to the existing inventory.
- **Add Item to Bill**: Generate bills for customers by deducting quantities from the inventory.
- **Print Bill**: Display the bill with the total amount.
- **Display Inventory**: Show the current items in the inventory along with their rates and quantities.

## Predefined Products

The program starts with predefined products in the inventory:
- `sooji-50kg` with a rate of 1500 and quantity of 50.
- `sugar-50kg` with a rate of 2200 and quantity of 50.
- `maida-50kg` with a rate of 1500 and quantity of 50.
- `atta-50kg` with a rate of 1350 and quantity of 50.

## Getting Started

### Prerequisites

- C++ compiler

### Running the Program

1. **Compile the program**:

   ```sh
   g++ -o inventory_organiser inventory_organiser.cpp
2. Run the executable:
   ./inventory_organiser
There Appears a program menu
Welcome To Ration Inventory Organiser
*************************************
1. Add Item to Inventory.
2. Update Inventory.
3. Add Item to Bill.
4. Print Bill.
5. Display Inventory.
6. Exit.
Enter Choice: 
EXAMPLE INTERACTION:
Welcome To Ration Inventory Organiser
*************************************
1. Add Item to Inventory.
2. Update Inventory.
3. Add Item to Bill.
4. Print Bill.
5. Display Inventory.
6. Exit.
Enter Choice: 1
    Enter Item Name (e.g., 'rice-50kg'): rice-50kg
    Enter Rate Of Item: 2000
    Enter Quantity Of Item: 10
    Item Added Successfully

Enter Choice: 2
    Enter Item Name to Update (e.g., 'rice-50kg'): rice-50kg
    Enter New Rate Of Item: 2100
    Enter New Quantity Of Item: 20
    Item Updated Successfully

Enter Choice: 5
    Item | Rate | Quantity
    sooji-50kg   1500     50
    sugar-50kg   2200     50
    maida-50kg   1500     50
    atta-50kg    1350     50
    rice-50kg    2100     30

Enter Choice: 6
    Good Luck!
