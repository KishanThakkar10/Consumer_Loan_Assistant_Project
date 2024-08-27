# Consumer Loan Assistant

## Overview
The **Consumer Loan Assistant** is a Java-based GUI application that helps users calculate either the monthly payment or the number of payments required for a loan. This tool is useful for anyone who needs to quickly determine their loan payment schedule based on simple input parameters.

## Features
- **Monthly Payment Calculation**: Compute the monthly payment for a loan based on the loan amount, interest rate, and number of payments.
- **Number of Payments Calculation**: Determine how many payments are required for a loan based on the loan amount, interest rate, and desired monthly payment.
- **Switchable Input Modes**: Easily switch between calculating monthly payments and the number of payments by toggling the relevant input fields.
- **Detailed Loan Analysis**: View the loan analysis results in a readable text area for easy reference.

## GUI Components
- **Labels (`JLabel`)**: Display text fields for loan balance, interest rate, number of payments, and monthly payment.
- **Text Fields (`JTextField`)**: Allow input of loan parameters.
- **Buttons (`JButton`)**:
  - **Compute Monthly Payment**: Performs the calculation based on user input.
  - **New Loan Analysis**: Resets the fields for a new calculation.
  - **Exit**: Closes the application.
  - **X Buttons**: Toggle between input modes for monthly payments and number of payments.
- **Text Area (`JTextArea`)**: Displays the loan analysis results.

## How to Use
1. **Enter Loan Details**:
   - Input the **Loan Balance** and **Interest Rate** in the provided text fields.
   - Either input the **Number of Payments** to calculate the **Monthly Payment**, or input the **Monthly Payment** to calculate the **Number of Payments**.
2. **Compute**:
   - Click on the "Compute Monthly Payment" button to perform the calculation.
3. **View Analysis**:
   - The results will be displayed in the "Loan Analysis" text area.
4. **New Analysis**:
   - Click on the "New Loan Analysis" button to reset the fields and start a new calculation.
5. **Switch Mode**:
   - Use the "X" buttons to toggle between calculating the monthly payment and the number of payments.
6. **Exit**:
   - Click the "Exit" button to close the application.

## Code Structure
- **Consumer_Loan_Assistant.java**: Contains the main class and logic for the application. It handles the GUI setup, event handling, and loan calculations.

## Prerequisites
- **Java Development Kit (JDK) 8 or higher**: Make sure you have the appropriate JDK installed to run the application.
