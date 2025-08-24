# Airgead Banking Investment Calculator

## Overview
A command-line C++ program that calculates and compares investment growth over time—with and without monthly deposits. This tool helps users visualize the impact of regular contributions on compound interest and assists with better savings planning.

## Motivation
This project was built as part of a programming course to demonstrate:
- Object-oriented design in C++
- Clear, maintainable, and well-documented code
- Financial growth logic emphasizing compounding and investment comparison

## Features
- **No Monthly Deposits:** Calculates yearly interest on the principal investment.
- **With Monthly Deposits:** Adds a monthly deposit, then compounds interest monthly.
- Displays year-by-year tables with balances and earned interest for both scenarios.

## Technologies Used
- **Language:** C++
- **Standard Libraries:**
  - `<iostream>` — for input and output operations
  - `<iomanip>` — for formatting numbers (aligning, setting precision)
  - `<cmath>` — available for future enhancements requiring math functions

## Installation & Running Instructions
1. Clone the repository and navigate into it.
2. Compile the program using:
   ```bash
   g++ InvestmentCalculator.cpp -o investment_calc

   What Went Well

Encapsulation: Using the InvestmentCalculator class keeps logic organized and clear.

Console Formatting: Numerical results look clean and aligned thanks to <iomanip>.

Functional Clarity: Users easily compare the effects of monthly deposits versus simple interest.

Challenges & Solutions

Monthly Compounding Logic: The nested year-month loop was tricky; I verified it manually using small test cases to ensure accuracy.

Output Formatting: Aligning the table neatly took trial and error until the columns lined up consistently.

Areas for Improvement

Input Validation: Currently, all inputs are accepted. Validating for non-negative values and reasonable interest rates would make it more robust.

Error Handling: Responding gracefully to invalid input (e.g., letters instead of numbers) would improve usability.

Extended Functionality: Possible future enhancements include variable interest rates, inflation adjustment, or CSV export.

Transferable Skills

Object-Oriented Programming (OOP): Fundamentals of class-based design in C++.

Loop Control & Logic: Handling nested loops for accurate compounding calculations.

Console UI Experience: Leveraging I/O formatting for clear CLI interactions.

Next Steps (Optional Enhancements)

Add input sanitization and error messages.

Author: gabdelmalik.ganiev@shnu.edu

Break apart logic into smaller functions or separate files for modularity.

Expand to support advanced financial modeling features or output formats.
