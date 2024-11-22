# E-commerce Project

## Project Overview
This project is a basic simulation of an e-commerce website created to practice Object-Oriented Programming (OOP) concepts. It demonstrates how to manage products, shopping baskets, payments, and shipment procedures in an online store.

### Concepts Covered:
- **Classes**: We created classes for `Product`, `ShoppingBasket`, `Payment`, and `Shipment`.
- **Encapsulation**: Each class has private variables, and we use methods to access or modify them.
- **Inheritance**: We use inheritance for different payment methods (`CreditCard` and `PayPal`) that extend a common base class (`Payment`).
- **Polymorphism**: Depending on user input, the correct payment method (CreditCard or PayPal) is selected and processed.
- **Abstract Classes & Interfaces**: We use an abstract class for `Payment` and interfaces for different shipment methods.

## Features
- Users can **add products** (Laptop or Phone) to the shopping basket.
- The program **calculates the total** price of selected items.
- Users can choose a **payment method** (Credit Card or PayPal).
- **Shipment details** are provided once payment is successful, and the shipment is "delivered."

### Classes and Their Functions:
- **Product**: Contains details like the name, price, stock, and product ID.
- **ShoppingBasket**: Holds the items the user selects and calculates the total cost of the basket.
- **Payment**: Processes payments based on the selected payment method (Credit Card or PayPal).
- **Shipment**: Collects the customer's address and delivery status, and simulates shipment delivery.

## How To Use:
1. **Run the Program**: Launch the program, and you will be greeted with options to add products to the basket.
2. **Select Products**: 
   - Type `1` to add a Laptop to the basket.
   - Type `2` to add a Phone to the basket.
3. **Checkout**: Type `3` to proceed to checkout.
4. **Choose Payment Method**: Select between Credit Card or PayPal.
5. **Enter Delivery Information**: Enter your name and address to complete the shipment.

### Example:
```plaintext
welcome to the E-commerce System
1. Add Laptop to Basket
2. Add Phone to Basket
3. Checkout
Choose an option: 1
Choose an option: 3
Customer: Ebrar
Address: Ankara/Etimesgut Türkkuşu Kampüsü
Delivery Status: Not Delivered
Shipment delivered to Ankara/Etimesgut Türkkuşu Kampüsü

welcome to the E-commerce System!
1. Add Laptop to Basket
2. Add Phone to Basket
3. Checkout
Choose an option: 4
Invalid choice. Try again.


## Group Members
- **Group Name**: TeamSoftware
- **Members**:
  - **Name**: Ebrar Ağralı, **ID**: 220446030
  - **Name**: İpek Demirel, **ID**: 220446049
  - **Name**: İlayda Kalender, **ID**: 220446040
  - **Name**: Melek Arslan, **ID**: 220446018


