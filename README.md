# Cafeteria Management System

A console-based Cafeteria Management System developed in C to manage customer orders, menu items, inventory, pricing, billing, and sales records.

## Overview

The Cafeteria Management System simulates the core operations of a cafeteria through an interactive command-line interface. It provides separate options for administrators and customers, allowing staff to manage menu information and inventory while customers can browse menus, place orders, and receive detailed bills.

The project was developed to apply fundamental C programming concepts to a practical management system.

## Features

### Customer Features

* Browse categorized menus
* Breakfast, brunch, and lunch options
* Pizza, burger, club sandwich, drinks, and samosa submenus
* Select item quantities
* Select sizes for applicable items
* Automatic stock availability checking
* Automatic stock deduction after ordering
* Drink reminder before completing an order
* Detailed customer bill
* Date and time displayed on the bill

### Billing System

* Automatic subtotal calculation
* 10% discount on qualifying orders
* 15% GST calculation
* Automatic final total calculation
* Transaction records stored in sales history

### Administrator Features

The administrator section is password protected and provides options to:

* Update menu prices
* Update item stock
* View current stock
* View sales history
* View overall sales

### Inventory Management

The system keeps track of stock for individual menu items. Stock is automatically reduced when an order is placed, and administrators can update stock quantities when required.

### Menu Management

The system includes the following categories:

* Breakfast
* Brunch
* Lunch
* Pizza
* Burgers
* Club Sandwiches
* Drinks
* Samosas

Items can have fixed prices or different prices based on size.

### File Handling

The system uses a text file named `cafeteria_menu.txt` to store menu prices and stock information.

Menu data is:

* Loaded when the program starts
* Created automatically if the file does not exist
* Updated whenever prices or stock are changed
* Preserved between program executions

## Technologies Used

* **C**
* Standard C libraries
* Windows Console API
* File Handling
* Structures
* Arrays
* Pointers
* Functions
* String Manipulation
* Date and Time Functions
* Random Number Generation

## Requirements

* Windows operating system
* C compiler such as GCC/MinGW
* C-compatible IDE or code editor

The project uses Windows-specific libraries such as `windows.h` and `conio.h`, so it is intended for Windows.

## Learning Objectives

This project was developed to gain practical experience with:

* C programming
* Structured programming
* Modular programming
* File handling
* Arrays and structures
* Pointers
* User input and validation
* Inventory management
* Transaction processing
* Applying programming concepts to a real-world scenario

## Future Improvements

* Persistent sales history using file storage or a database
* Improved input validation
* Low-stock notifications
* Customer order history
* Daily, weekly, and monthly sales reports
* Improved authentication
* Employee account management
* Graphical user interface
* Database integration
