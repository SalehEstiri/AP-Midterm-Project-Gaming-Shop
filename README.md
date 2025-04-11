# Game Store Management System

## Overview
This is a C++ console-based application that simulates a game store management system with two types of users: Admin and Customer. The system allows admins to manage products (games, consoles, headsets, monitors) and customers to browse and purchase items.

## Features

### Admin Features
1. Add Product: Add new products to the store inventory
2. Delete Product: Remove products from the store
3. Search Product: Find products by name
4. Show All Products: Display all available products with details
5. Total Price of Products: Calculate total value of all products
6. Store Wallet Recharge: Add funds to the store's wallet
7. Store Wallet Balance: Check current store balance
8. Show Inventory: View inventory counts for all product categories

### Customer Features
1. Search Product: Find products by name
2. Show All Products: Browse available products
3. Wallet Recharge: Add funds to personal wallet
4. Shopping Cart:
   - View cart balance
   - View cart contents
   - Add items to cart
   - Purchase items

## Product Categories
1. Games
2. Consoles
3. Headsets
4. Monitors

## Technical Details
- Implemented in C++ using object-oriented programming
- Uses inheritance with a base Product class
- Stores products in separate vectors for each category
- Implements search functionality (linear search)
- Manages separate wallets for admin and customer
- Tracks inventory levels

## Usage
1. Compile the program using a C++ compiler (e.g., g++)
2. Run the executable
3. Choose to login as admin or customer
   - Admin password: "admin1admin"
4. Follow the menu options to perform actions

## Requirements
- C++ compiler (C++11 or later recommended)
- Standard Library headers: <iostream>, <string>, <vector>

## Notes
- All data is stored in memory and will be lost when the program exits
- The program uses console input/output for interaction
- Basic error handling is implemented for invalid inputs

## Future Improvements
1. Add persistent data storage (file or database)
2. Implement more sophisticated search algorithms
3. Add product categories and attributes
4. Implement user accounts with authentication
5. Add transaction history
6. Improve UI with more formatting and colors
