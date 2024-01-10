
![Travel Managemntdrawio](https://github.com/varmadatla07/Travel-management-Project/assets/126235366/30418bdc-bd72-4040-a513-240a9356c1d9)

# ABC Travels Management System

This C++ program is a simple management system for ABC Travels, covering customer management, cab services, hotel bookings, and billing. The program utilizes various classes and inheritance for better organization and structure.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Classes](#classes)
- [File Structure](#file-structure)
- [Compilation](#compilation)
- [License](#license)

## Overview

ABC Travels Management System is designed to facilitate the management of customers, cab services, hotel bookings, and billing. The program allows users to input customer details, choose cab services, book hotels, and generate receipts for the services availed.

## Features

- **Customer management:** Input and display customer details.
- **Cab services:** Choose between standard and luxury cabs, calculate costs, and hire cabs.
- **Hotel bookings:** Book rooms in collaborating hotels with different packages.
- **Billing:** Generate a receipt that includes hotel and cab costs.

## Usage

1. Run the program.
2. Enter your name to log in as an admin.
3. Choose from the main menu options:
   - Customer Management
   - Cab Services
   - Hotel Bookings
   - Billing
   - Exit

## Classes

1. **ManageMenu**
   - Base class for managing the main menu and user login.
   - Takes user name input and displays the main menu.

2. **Customer**
   - Manages customer details, such as ID, name, age, mobile number, address, and gender.
   - Allows the input of customer details and displays old customer records.

3. **Cabs**
   - Handles cab details, including types, costs, and hiring.
   - Calculates the cost based on the type of cab and distance.

4. **Booking**
   - Manages hotel bookings and associated costs.
   - Allows users to choose from collaborating hotels and different packages.

5. **Chargers**
   - Inherits from `Booking`, `Cabs`, and `Customer`.
   - Prints and displays the final bill, including hotel and cab costs.

## File Structure

- `main.cpp`: Main program file.
- `old-customers.txt`: File to store details of old customers.
- `receipt.txt`: File to store the generated receipt.

## Compilation

To compile the program, use a C++ compiler:

```bash
g++ main.cpp -o ABC_Travels_Management_System

