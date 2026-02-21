# Task 01: Calculator Application Test Cases

**Intern Name:** Vaishnavi Sunil Sonawane  
**Domain:** Software Testing  
**Task:** Create detailed test cases for a calculator.

### **Positive Scenarios**
| Test Case ID | Description | Preconditions | Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Tc-01 | Addition of 2 numbers | Calculator is Open | 1. Enter 50, 2. Press '+', 3. Enter 30, 4. Press '=' | Result: 80 | Pass |
| TC-02 | Subtraction with negative result | Calculator is Open | 1. Enter 10, 2. Press '-', 3. Enter 25, 4. Press '=' | Result: -15 | Pass |
| TC-03 | Multiplication | Calculator is Open | 1. Enter 2, 2. Press '*', 3. Enter 4, 4. Press '=' | Result: 8 | Pass |
| TC-04 | Division | Calculator is Open | 1. Enter 10, 2. Press '/', 3. Enter 2, 4. Press '=' | Result: 5 | Pass |

### **Negative Scenarios**
| Test Case ID | Description | Preconditions | Steps | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| TC-05 | Division by Zero | Calculator Open | 1. Enter 10, 2. Press '/', 3. Enter 0, 4. Press '=' | Error: "Cannot divide by zero" | Pass |
| TC-06 | Empty Input | Calculator Open | 1. Press '+' without numbers | No action or 0 displayed | Pass |
| TC-07 | Multiple Operators | Calculator open | 1. Press '+', 2. Press '-' | Should take the last operator | Pass |
