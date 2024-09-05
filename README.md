# Hotel-Management-System-In-Python
This is a Python-based console application that simulates a basic hotel management system. The system allows users to perform tasks such as booking rooms, checking room information, placing restaurant orders, processing payments, and viewing booking records.

Features->
1.Room Booking:
Allows customers to book different types of rooms (Non-AC, AC, etc.), assigns a customer ID, and stores booking details.

2.Room Information:
Displays information about the various types of rooms available, including features and amenities.

3.Restaurant Menu:
Provides a menu of available food items, allows customers to place orders, and calculates the total bill.

4.Payment:
Calculates the total bill (including room booking and restaurant charges) and provides different payment methods (Cash, Card, UPI).

5.Booking Records:
Displays all room booking records with customer details.

# How to Run
Prerequisites:

Python 3.x installed on your system.

Execution:

Run the program in the terminal or command prompt by executing the Python script.

You will be prompted to input the number of times the system should run.

# Example Execution:
 python hotel_management.py

User Navigation:

After running the program, you will be presented with a main menu with the following options:

1.Booking: Starts the room booking process.

2.Room Info: Shows details of available rooms.

3.Restaurant: Displays the restaurant menu and takes orders.

4.Payment: Calculates and processes payment.

5.Record: Displays all booking records.

6.Exit: Exits the program.

Navigate by entering the corresponding number for each action.

# Code Structure

1. Home(): The main function that serves as the entry point and menu navigator.

2. BOOKING(): Handles room booking, assigns room numbers, customer IDs, and stores customer information.

3. Room_info(): Displays details about the room types.

4.Restaurant(): Allows customers to order food and calculate their total restaurant bill.

5.Payment(): Processes payment, adding up room and restaurant charges, and allows different payment methods.

6.Record(): Displays all booking records.

# Future Improvements

Enhance the user interface with better error handling and input validation.

Save booking records and payment details to a database or file for persistence.

Expand the restaurant menu and include more room types with dynamic pricing.
