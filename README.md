# Calculator App Documentation

## Overview

This simple calculator app, developed in Java, is designed to perform basic mathematical operations. It provides a user-friendly interface for performing addition, subtraction, multiplication, and division.

## Features

### 1. Addition

The calculator allows users to add two numbers. Upon entering the numbers and clicking the "+" button, the app displays the sum of the two values.

### 2. Subtraction

Users can perform subtraction by entering two numbers and clicking the "-" button. The app then displays the result of subtracting the second number from the first.

### 3. Multiplication

Multiplication functionality is available by entering two numbers and clicking the "*" button. The app calculates and displays the product of the entered values.

### 4. Division

For division, users can input two numbers and click the "/" button. The app calculates and displays the quotient of dividing the first number by the second.

## How to Use

1. **Input**: Enter numerical values for the two operands in the designated input fields.
2. **Operation Selection**: Click on the appropriate operation button (+, -, *, /) based on the desired mathematical operation.
3. **Result Display**: The app will display the result of the operation in a designated area.

## Sample Code

```java
// Sample code snippet from the code*
switch(operator) {
    case '+':
        result = (float) (num1+num2);
        break;
    case '-':
        result = (float) (num1-num2);
        break;
    case '*':
        result = (float) (num1*num2);
        break;
    case '/':
        result = (float) (num1/num2);
        break;
        
			}
