🛒 Shopping Cart Billing System – Python Project

 Overview :- 

This project is a Python-based Shopping Cart Billing System that allows users to select items, manage a cart, apply discounts, and generate a receipt. It simulates a real supermarket billing experience through a command-line interface (CLI).


Features :-

✔ Login system
✔ 30-item product database (price + stock)
✔ Add items to cart
✔ Remove items from cart
✔ Stock validation
✔ Coupon system (SAVE10 → 10% OFF)
✔ Automatic bill calculation
✔ Frequency table at checkout
✔ Receipt generation (receipt.txt)
✔ Random order ID and delivery date

--------


⚙ Setup Instructions

1. Requirements
Python 3.8 or higher
No external libraries required (uses built-in modules)
2. How to Run
Open terminal / command prompt and run:
python main.py


🧩 Code Details

Modules Used
Module	Purpose
random	Generate order ID & delivery date
datetime	Calculate delivery date
collections.Counter	Frequency table


🏗 Main Functionalities

login()
, Prompts username and starts session.
, display_items()
Shows all 30 products with price and available stock.
, add_to_cart()
1. Validates product
2. Validates quantity
3. Deducts stock
4. Adds selected quantity to cart
, remove_from_cart()
1. Shows current cart
2. Removes chosen quantity
3. Restores stock
, apply_coupon()
Applies 10% discount if code is SAVE10.
, checkout()
1. Creates frequency table
2. Computes bill
3. Generates order ID
4. Estimates delivery date
5. Saves receipt
, save_receipt()
Generates receipt.txt with:
Customer name
Order ID
Item list
Final amount
Delivery date


📄 Receipt Output

After checkout, a receipt file is saved as:
receipt.txt
Containing order details, price breakup, and delivery information.


📝 Author

This project was developed as part of a Python programming focusing on data structures, user interaction, and file handling.
