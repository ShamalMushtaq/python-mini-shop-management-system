🛒 Mini Shop Management System

A simple menu-driven Python console application that helps a small shop owner manage products, track stock, process sales, and view business summaries — built as a beginner Python project to practice core language concepts in a real, working program.

📋 Features
Add Product — store product ID, name, price, quantity, and category
View Products — list all products currently in the shop
Search Product — find a product by ID or by (partial) name
Sell Product — checks stock, calculates total, generates a bill, and updates inventory
Low Stock Report — flags products with fewer than 5 units left
Sales Summary — shows total items sold and total revenue
Bonus: Sort products by price (lambda function)
Bonus: Search products by name
Handles invalid input gracefully (duplicate IDs, non-numeric input, out-of-stock sales, etc.)
🧠 Python Concepts Used
Concept	Where it's used
while loop	Keeps the main menu running
for loop	Displaying products
Nested loop	Processing sales in the summary
break / continue / pass	Menu exit, skipping empty input, placeholder handling
Functions (params, return values, scope)	add_product(), search_product(), sell_product(), etc.
List, Tuple, Dictionary, Set	Storing sales, categories, product data, and unique categories
List comprehension	Finding low-stock products
Dictionary comprehension	Building a name → price lookup
Lambda function	Sorting products by price
Recursion	Counting total sale entries on exit
🚀 How to Run
Make sure you have Python 3 installed.
Clone this repository:
bash
   git clone https://github.com/<your-username>/mini-shop-management-system.git
   cd mini-shop-management-system
Run the program:
bash
   python3 mini_shop_system.py
🖥️ Sample Menu
================================
     MINI SHOP SYSTEM
================================

1. Add Product
2. View Products
3. Search Product
4. Sell Product
5. Check Low Stock
6. Sales Summary
7. Sort Products by Price (bonus)
8. Search by Name (bonus)
9. Exit

Enter your choice:
📸 Screenshots
Feature	Preview
Adding a Product	screenshots/Add_product_glass.png
Viewing Products	screenshots/view_product.png
Searching a Product	screenshots/Screenshot_2026-09-20_174659.png
Selling a Product	screenshots/Screenshot_2026-09-20_180136.png
Low Stock Report	screenshots/Screenshot_2026-09-20_180435.png
Sales Summary	screenshots/Screenshot_2026-09-20_180604.png

Full walkthrough with all screenshots and captions is available in Mini_Shop_System_Report.pdf.

📁 Project Structure
mini-shop-management-system/
├── mini_shop_system.py          # Main program
├── README.md                    # Project documentation
├── Mini_Shop_System_Report.pdf  # Full screenshot walkthrough
└── screenshots/                 # Individual screenshots
🎯 Project Goal

This project was built as part of a Python fundamentals assignment, with the goal of applying core concepts — loops, functions, data structures, comprehensions, lambda functions, and recursion — inside one small, working, real-world program.

📝 License

This project is free to use for learning and educational purposes.
