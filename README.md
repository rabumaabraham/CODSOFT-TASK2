# Calculator CLI Application

This is a fully functional Calculator CLI Application built using python, during my python programming internship at CodSoft. This simple Calculator CLI Application allows users to perform basic arithmetic operations, such as addition, subtraction, multiplication, and division. The application prompts the user to input two numbers and an operation, and then calculates and displays the result.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Example Usage](#example-usage)

## Features

- Addition: Adds two numbers.
- Subtraction: Subtracts the second number from the first.
- Multiplication: Multiplies two numbers.
- Division: Divides the first number by the second (with error handling for division by zero).
- Error Handling: Handles invalid numeric input and division by zero gracefully.

## Technologies Used

- Python

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/rabumaabraham/CODSOFT-TASK2/tree/main
    ```

2. **Navigate into the project directory**:

    ```bash
    cd Calculator
    ```

3. **Run the application**:

    python calculator.py


## Example Usage

Enter the first number: 5
Enter the operation (+, -, *, /): +
Enter the second number: 3
5.0 + 3.0 = 8.0

Do you want to continue calculation? (Y/N): Y

Enter the first number: 10
Enter the operation (+, -, *, /): /
Enter the second number: 2
10.0 / 2.0 = 5.0

Do you want to continue calculation? (Y/N): N
Goodbye!
