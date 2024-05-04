# Calculator Class

This is a Python class that provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Usage

Instantiate the `Calculator` class with two numbers, and then use its methods to perform arithmetic operations.

```python
# Example usage:
calc = Calculator(10, 5)
print("Addition:", calc.add())
print("Subtraction:", calc.subtract())
print("Multiplication:", calc.multiply())
print("Division:", calc.divide())
```

## Methods

- `add()`: Adds the two numbers.
- `subtract()`: Subtracts the second number from the first.
- `multiply()`: Multiplies the two numbers.
- `divide()`: Divides the first number by the second. If the second number is zero, a `ZeroDivisionError` is raised.

## Example

```python
# Instantiate the calculator with numbers 10 and 5
calc = Calculator(10, 5)

# Perform arithmetic operations
print("Addition:", calc.add())           # Output: 15
print("Subtraction:", calc.subtract())   # Output: 5
print("Multiplication:", calc.multiply())# Output: 50
print("Division:", calc.divide())       # Output: 2.0
```

## Error Handling

If attempting to divide by zero, a `ZeroDivisionError` will be raised.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```


