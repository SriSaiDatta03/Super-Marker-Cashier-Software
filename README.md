Supermarket Cashier Software 🛒💼
-
---

Overview:
-
The Supermarket Cashier Software is a robust Python application designed to streamline the process of product entry, price calculation, and discount application based on customer membership levels. This user-friendly system enhances the efficiency of supermarket cashiers, allowing them to manage transactions effectively.

---

Features ✨


Product Entry: Easily add multiple products along with their respective quantities.

Price Calculation: Automatically computes the subtotal for each product based on a predefined pricing structure.

Discount Application: Provides discounts based on customer membership tiers (Gold, Silver, Bronze) for total bills exceeding $25.

User-Friendly Interface: Intuitive command-line interface for seamless interaction.

---

Getting Started 🚀
-

Prerequisites

Python 3.x installed on your machine.

Basic understanding of running Python scripts.

-

Installation

Clone this repository or download the script files.

Ensure that Python is properly installed and configured on your system.

Running the Application

Open your terminal or command prompt.

Navigate to the directory containing the script.

Execute the script using the command:

```bash
python supermarket_cashier_software.py
```

Follow the prompts to enter product details and customer membership information.

---

How to Use 📝

Add Products:

When prompted, press A to add a product.

Input the product name and quantity.

Repeat this step to add additional products as needed.

Quit Adding Products:

Press Q when you have finished entering products.

Enter Membership Level:

After completing product entry, you will be asked to input the customer’s membership level (Gold, Silver, or Bronze).

View Bill:

The system will display a detailed bill including product prices, quantities, subtotal, and any applicable discounts.

Example Output 📊

Here’s an example of how the interaction might look:
```
Press A to add product and Q to quit: A
Enter product: Biscuit
Enter quantity: 5
Press A to add product and Q to quit: A
Enter product: Chicken
Enter quantity: 3
Press A to add product and Q to quit: Q
Enter customer membership: Gold
Biscuit:$3x5=15
Chicken:$5x3=15
The discounted amount is $24.0 (20% off for Gold membership on total amount)
```

Code Structure 🛠️
-

Functions

enterProducts(): Manages user input for adding products and their quantities.

getPrice(product, quantity): Calculates the price for each product based on its quantity.

getDiscount(billAmount, membership): Applies discounts according to membership level if applicable.

makeBill(buyingData, membership): Generates the final bill by calculating totals and applying discounts.

---

Contribution 🤝
-
Contributions are highly encouraged! Feel free to submit issues or pull requests. Your feedback is invaluable in enhancing this application!

HAPPY SHOPPING 🛒...
