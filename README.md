# Offset Loan Calculator

A web-based calculator that simulates loan repayments with an offset account, helping borrowers understand the impact of their offset balance and income on loan duration and interest payments.

## Demo

Try it live: [Offset Loan Calculator Demo](https://offset-loan-calculator.vercel.app/)

## Features

- Calculate loan repayment schedule considering:
  - Loan amount
  - Offset account balance
  - Annual interest rate
  - Fortnightly loan payments
  - Regular income deposited to offset account
- Interactive chart visualization showing:
  - Remaining loan balance over time
  - Offset account balance
  - Interest paid per fortnight (toggleable)
- Key statistics display:
  - Total loan duration in years and months
  - Total interest paid over the life of the loan
- Persistent storage of input values
- Mobile-responsive design
- Example scenario for quick testing

## Usage

1. Enter your loan details:

   - Loan Amount: The total amount borrowed
   - Offset Balance: Current balance in your offset account
   - Annual Interest Rate: Enter as decimal (e.g., 0.0549 for 5.49%)
   - Fortnightly Loan Payment: Regular payment amount
   - Fortnightly Income: Income deposited into offset account

2. Click "Run Simulation" to see results
3. Use "Reset" to clear all inputs
4. Try "Example Scenario" to see a sample calculation

## Technical Details

- Built with vanilla JavaScript and HTML5
- Uses Chart.js for data visualization
- Implements local storage for saving input values
- Performs fortnightly calculations considering:
  - Interest savings from offset balance
  - Regular income deposits
  - Principal and interest components

## Browser Support

Works in all modern browsers that support:

- ES6+ JavaScript
- HTML5 Canvas
- LocalStorage API
- CSS Grid and Flexbox

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright © 2025 Anthony Dinino
