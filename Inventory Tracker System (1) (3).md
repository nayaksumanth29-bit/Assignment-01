\# Inventory Tracker System 

\## Overview 
The Inventory Tracker System is a menu-driven,console-based Python application designed to help users manage and monitor inventory items efficiently. It allows users to add items, viewinventory details, search for specific products, and store inventory data permanently using file handling.
This project is developed as part of the Python Mini Project assignment and demonstrates the practical use of core Python concepts taught in class.

\-\--

\## Problem Addressed 
Managing inventory manually can lead to: 
- Stock shortages or overstocking
- Errors in maintaining item records
- Difficulty in searching specific items
- Loss of data due to lack of storage

This project provides a simple digital solution for organizing inventory data accurately and efficiently.

\-\--

\## Main Features 
- Add Inventory Item -- Adds new inventory records with item details
- View Inventory -- Displays all available inventory items
- Search Inventory by Item ID -- Finds a specific iem using its unique ID
- Menu-driven Interface -- Allows users to choose operationsthrough a menu
- Input Validation -- Prevents incorrect inputs and handles errors safely
- Data Persistence -- Stores inventory data in a file for future use

\-\--

\## Python Concepts Used

\### Data Structures 
- Dictionary -- Stores inventory data with keys representing item attributes
- Lists -- Used as values inside the dictionary to store multiple records
- Dictionary of Lists Structure -- Each index represents one inventory item

\### Control Flow 
- while loop -- Repeats menu until the user exits  
- if / elif / else -- Handles menu selection and decision logic
- for loop -- Iterates through inventory records
  
\### Functions 
- show_menu() -- Displays menu options
- add_item() --  Adds a new inventory item
-view_inventory() -- Displays all inventory records
- search_item() -- Searches inventory using Item ID 
- delete_item() -- Deletes an inventory record
- save_to_file() -- Saves inventory data to a file
- load_from_file() -- Loads inventory data from a file  
- exit_program() -- Exits the program safely

\-\--

\## Methods Used

\### List Methods 
- append() -- Adds new inventory data
- pop() -- Removes inventory records
- len() -- Counts inventory items

\### Dictionary Methods
- keys() -- Accesses dictionary keys
- values()-- Accesses dictionary values
- get() -- Retrieves values safely

\### String Methods 
- strip() -- Removes extra spaces from input  -
- title() -- Formats item names properly

\-\--

\## Exception Handling
- try / except blocks are used to handle invalid user input
- Prevents program crashes due to incorrect data types
- Displays user-friendly error messages

\-\--

\## File Handling and Libraries 
- Inventory data is saved and loaded using \`with open()\`
- Files are opened in read (\`\"r\"\`) and write (\`\"w\"\`)modes
- Ensures data persistence across executions
- Uses only standard Python libraries

\-\--

\## How to Run

\### Requirements - Python 3.x - Jupyter Notebook or Python IDLE / VS
Code

\### Steps 
1. Download:  - inventory_tracker.ipynb orinventory_tracker.py  - inventory.txt
2. Place both files in the same folder
3. Open Jupyter Notebook: \`\`\`bash jupyter notebook
4. Inventory Tracker System Python Mini Project -- Inventory Tracker


\## Input and Usage Guidelines

- Item ID, Quantity, and Unit Price must be entered as numeric values.
- Item Name and Category should be entered as text.
- Menu options must be selected using numbers only. 
- Invalid input will display an appropriate error message.
- Always choose the Exit option to
- save data safely before closing the program.

\-\--

\## File and Dataset Details

\- Data File Name -- \`inventory.txt\` 
- File Location -- Stored in the same folder as the Python program.
- Stored Fields -- Item ID, Item Name, Category, Quantity, Unit Price.
- File Creation -- The file is automatically created if it does not exist.
- Data Loading -- Inventory data is loaded from the file when the program starts.

\-\--

\## Assignment Fit and Extras

- Fully meets Python mini-project requirements.
- Solves a real-world inventory management problem.
- Uses structured and modular programming techniques.
- Includes exception handling and file handling.
- Easy to extend with additional features if required.

\-\--

\## Author and Project Information

Name: Sumanth Nayak - USN: 1BG24BA133
Course: Python Programming  -
Project: Inventory Tracker System 
Domain: Inventory / Retail Management
