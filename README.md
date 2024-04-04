# Expense Tracker

A simple expense tracker implemented in Python, utilizing lists, dictionaries, lambda functions, and control structures.

## Description

This project aims to create a basic expense tracker in Python. It leverages fundamental concepts such as lists, dictionaries, lambda functions, and control structures to enable users to add, list, filter, and calculate total expenses.

## How to Use

1. **Add an Expense:** Enter the amount and category of the expense.
2. **List all Expenses:** View all expenses entered so far.
3. **Show Total Expenses:** Get the sum of all expenses.
4. **Filter Expenses by Category:** View expenses filtered by a specific category.
5. **Exit:** Terminate the program.

## Python Concepts Used

- **Lists:** Used to store expense data.
- **Dictionaries:** Store expense details as key-value pairs.
- **Lambda Functions:** For concise, anonymous functions.
- **Control Structures:** Utilized for user interaction and program flow control.
- **Input Function:** Collect user input.
- **Float Function:** Convert input to floating point numbers.
- **Map Function:** Apply a function to all elements of a list.
- **Filter Function:** Select items from a collection based on a condition.

## Learnings

This project provides hands-on experience in Python programming, especially in handling data structures, user input, and functional programming concepts like lambda functions and map/filter functions.

## Example

```python
test = lambda x: x * 2
print(sum(map(test, [2, 3, 5, 8])))
```
This code demonstrates the use of lambda and map functions to double each element in the list and then calculate their sum.

## Running the Program

To run the expense tracker, execute the script. Ensure to utilize the __name__ variable to identify if the script is being run as the main program or imported as a module.

```python
if __name__ == '__main__':
    main()
```
With this, the expense tracker project is ready for use!

Feel free to contribute, enhance, or customize it further as per your requirements. Happy tracking! 📊💰
