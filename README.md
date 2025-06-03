
# Café Management System ☕🍽️
Welcome to CAFE, a simple and interactive <b> Café Management System </b> built using Python. This system allows users to view <b> the menu, place orders, and generate bills </b> seamlessly.

## Features
✅ Interactive user experience ✅ Food menu display with item prices ✅ Ordering system with real-time bill updates ✅ Ability to add multiple items to the order ✅ Option to exit anytime

## Table of Contents
<u1>
  
<li>Installation</li>
<li>Usage</li>
<li>Add Menu</li>
<li>Functions</li>
<li>Example Run</li>
<li>icense</li>
</u1>

## Installation
No special installation is required! Simply run the Python scrip
```c
python cefe.py
```
## Usage
1️⃣ Run the script. 2️⃣ Select an option from the menu:
<u1>
<li>View Food Menu 🍽️</li>
<li>Order Food 🛎️</li>
<li>Exit 🚪 3️⃣ Place orders by entering item names. 4️⃣ View the final bill before exiting</li>
</u1>

## Food Menu
```c
food_menu = {
    "Pizza": 100,
    "Burger": 50,
    "Coffee": 40,
    "Fries": 60
}
```
Each item has a price (₹) assigned, which is updated in the bill upon ordering.

## Functions
welcome_customer()
Displays a warm welcome message.

show_menu()
Prints the list of available food items with their respective prices.

take_order()
Handles customer orders and updates the total bill dynamically.

cefe_menu()
Provides a main menu to navigate through different options.

## Example Run
```c
🌟 Welcome to CEFE! 🌟
Enjoy delicious food and a great experience.

🌟 CEFE Management Menu:
1️⃣ View Food Menu
2️⃣ Order Food
3️⃣ Exit

Enter your choice: 2

Enter the item name to order (or type 'done' to finish): Pizza
✅ Pizza added to your order! Current bill: ₹100

Would you like to order anything else? (yes/no): no

🛎️ Final Bill: ₹100
🙏 Thank you for visiting CEFE! Have a great day! 🚀
```
## Enhancements & Possible Improvements
✅ Feature Upgrades
<u1>
<li>Add Discounts or Coupons for bulk orders.</li>
<li>Introduce User Authentication to track customer preferences.</li>
<li>Implement a Database System for dynamic menu changes.</li>
<li>Enhance UI using graphical frameworks (like Tkinter for Python GUI).</li>
</ul>
✅ Code Optimization
<ul>
<li>The billing system could use a class-based approach for better encapsulation.</li>
<li>Consider using exception handling (try-except blocks) to prevent input errors.</li>
<li>Implement unit testing to validate menu updates and order processing.</li>
</ul>
## Final Thoughts
This Café Management System is a simple yet effective implementation of order processing. It offers a user-friendly experience with clear instructions and an interactive menu.

