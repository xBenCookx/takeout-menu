# Module 21 Challenge: Takeout Restaurant Menu and Order System

## Description

This project consisted of me using my new Python skills to build out a program that allows customers to place orders with a takeout restaurant, and receive an itemized receipt.

The core skills I utilized from my coding experience, specifically Python, will be conditionals, loops, functions, and list comprehension. Data used in this Challenge will be stored in a dictionary and a list of dictionaries. I also used the Xpert learning assistant application to help clean and review my code.

## Implementation Details

The order system has been implemented with the following features:

### `place_order()` Function

- Creates a continuous ordering loop that allows customers to order multiple items
- Displays the menu with item numbers, categories, names, and prices
- Handles menu selection and quantity input
- Calculates the total order price using list comprehension
- Returns both the order list and the total price

### `update_order()` Function

- Validates user input for menu selection
- Handles quantity input with a default value of 1 for invalid inputs
- Creates order entries with item name, price, and quantity
- Provides clear error messages for invalid inputs
- Returns the updated order list

### `print_itemized_receipt()` Function

- Displays a formatted receipt with itemized details
- Shows each item's name, price, and quantity
- Calculates and displays the total order price
- Uses helper functions for consistent formatting

## User Story

```text
AS A hungry customer with hearing and vocal impairments
I WANT to view a menu, place an order, and see my receipt
SO THAT I don't have to interact with a person until I collect my food
```

## Acceptance Criteria

```text
GIVEN A restaurant order system
WHEN I launch the program
THEN I view all of the menu items listed with their category, name, and price
WHEN I select an item from the menu by entering a number
THEN I am asked the quantity of that item I want to order
WHEN I choose the quantity
THEN I am asked if I would like to continue ordering or not
WHEN I don't choose a valid quantity
THEN I automatically receive 1 of that menu item
WHEN I continue ordering
THEN I view the menu again
WHEN I quit ordering
THEN I am shown my itemized order receipt and total price
WHEN I enter an invalid response for the menu item
THEN I am given an error message
```

## Mock-Up

The following image shows a mock-up of the restaurant menu and ordering system:

!["Mock-up of the restaurant menu in Terminal"](./Assets/python-terminal-menu.png)

The following image shows a mock-up of the customer's receipt at the end of the program:

!["Mock-up of the customer's receipt in Terminal"](./Assets/python-terminal-receipt.png)

The following image shows a mock-up of the customer typing incorrect inputs for the menu options:

!["Mock-up of the customer typing incorrect menu options."](./Assets/incorrect-menu-options.png)

## Questions

If you have any questions, feel free to reach out to me:

- **GitHub:** [xBenCookx](https://github.com/xbencookx)
- **Email:** bencook1023@gmail.com
