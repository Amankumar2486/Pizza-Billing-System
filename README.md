# Pizza Billing system Program

This is a simple Python script that calculates the final bill for a pizza order based on the selected size and optional add-ons.

## Features

- Asks the user for pizza size: Small (S/s), Medium (M/m), or Large (L/l).
- Adds base price according to size:
  - Small: 100 Rs
  - Medium: 200 Rs
  - Large: 300 Rs
- If an invalid size is entered, defaults to a Large pizza (300 Rs).
- Optionally adds:
  - Pepperoni: 30 Rs for Small, 50 Rs for Medium/Large
  - Extra cheese: 20 Rs for any size
- Prints the final bill amount.

## How It Works

1. The program asks for the pizza size and initializes `bill = 0`.
2. According to the size, it adds the base price and prints the chosen pizza price.
3. If the size is invalid, it prints a warning and charges for a Large pizza.
4. Then it asks if the user wants pepperoni:
   - If yes and size is Small, add 30 Rs.
   - If yes and size is Medium or Large (or defaulted), add 50 Rs.
5. Next it asks if the user wants extra cheese:
   - If yes, add 20 Rs.
6. Finally, it prints the total bill in the format: `Final bill: <amount> Rs`.


