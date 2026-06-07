# Discount Calculator

A Python function that calculates the final price of an item after applying a percentage discount.

## Features

* Validates user inputs
* Checks whether price and discount are numbers
* Ensures price is greater than 0
* Ensures discount is between 0 and 100
* Calculates the discount amount
* Returns the final discounted price

## Function

```python
apply_discount(price, discount)
```

### Parameters

* `price` : Original price of the item
* `discount` : Discount percentage

### Example

```python
apply_discount(100, 20)
```

Output:

```python
80
```

### More Examples

```python
apply_discount(200, 50)
# Output: 100

apply_discount(50, 0)
# Output: 50

apply_discount(74.5, 20.0)
# Output: 59.6
```

## Concepts Used

* Functions
* Parameters
* Conditional Statements
* Type Checking
* Arithmetic Operations

## Author

Niharika
