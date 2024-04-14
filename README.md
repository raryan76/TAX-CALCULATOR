# TAX-CALCULATOR

A simple tax calculator implemented in JavaScript.
We are using practical design factory and strategy design pattern and on the basis of age factor we are returning different object for startgey class where I am implementing different logic for tax calculation on the basis of age factor in different startgey class, due to this code will exitensible and maintable and robust and also follow  open and close principal of SOLID .
we make it just using -HTML,CSS,JAVA SCRIPT.

## Test Cases

### Test Case 1: Valid Input

![Test Case 1](valid-input.png)

*Description:* This test case checks the calculation of taxes using valid input values.
- Input:
  - Gross Annual Income: 4000000
  - Extra Income: 0
  - Age: 34
  - Total Deductions: 0
- Expected Outcome: The overall income will be 3040000.

### Test Case 2: Invalid Input

![Test Case 2](invalid-input.png)

*Description:* This test case validates the handling of invalid input values.
- Input:
  - Gross Annual Income: $100,000
  - Extra Income: $20,000
  - Age: "ABC" (Invalid input)
  - Total Deductions: $8,000
- Expected Outcome: The tax calculator should display an error message for the invalid age input.

### Test Case 3: Boundary Conditions

![Test Case 3](Boundary-condition-output.png)
*Description:* This test case evaluates the tax calculation at boundary conditions.
- Input:
  - Gross Annual Income: 800,000 (Equal to base amount)
  - Extra Income: 0
  - Age: 59 (Close to upper age limit for a tax bracket)
  - Total Deductions: 50,000
- Expected Outcome: The overall income after tax should be calculated accurately.
