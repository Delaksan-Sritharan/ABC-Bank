# ABC Bank Management System

## Overview
The ABC Bank Management System is a simple Python-based console application that allows bank employees to manage customer accounts efficiently. It provides functionalities for adding new customers, viewing account details, making deposits and withdrawals, and updating customer information.

## Features
- Add a new customer with a unique 10-digit bank account number.
- View details of a specific customer, including bank balance.
- Display all customer details with their bank balances.
- Deposit money into a specific bank account.
- Withdraw money from a specific bank account.
- Update customer details such as NIC, name, phone number, and address.
- Ensure proper input validation for NIC, date of birth, phone number, and names.
- Prevent exceeding a limit of 5 customers.

## Technologies Used
- Python (Standard Library)
- Random module (for generating unique account numbers)

## Prerequisites
- Python 3.x installed on your system

## Installation & Usage
1. Clone the repository or download the script.
2. Run the script using:
   ```bash
   python bank_management.py
   ```
3. Follow the on-screen menu to perform operations.

## Input Validation Rules
- NIC must be 10 characters long, with the first 9 as digits and the last as an alphanumeric character.
- First name should be up to 10 alphabetical characters.
- Last name should be up to 15 alphabetical characters.
- Phone number must be a 10-digit numeric value.
- Address should not exceed 15 characters.
- Date of birth should be in YYYY-MM-DD format with proper validation.
- Deposits and withdrawals must be valid floating-point numbers.

## Future Enhancements
- Implement a database for persistent storage.
- Add authentication for security.
- Introduce GUI-based interaction.

## License
This project is open-source and available for modification and distribution under the MIT License.

