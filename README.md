# Mean-Variance-Standard Deviation Calculator

A Python calculator that analyzes lists of 9 numbers by converting them into a 3x3 matrix and calculating various statistics using NumPy.

## What It Does

Given a list of 9 numbers like `[0,1,2,3,4,5,6,7,8]`, this calculator:
1. Converts it into a 3x3 matrix
2. Calculates these statistics:
   - Mean (average)
   - Variance
   - Standard deviation
   - Max value
   - Min value
   - Sum

Each calculation is done three ways:
- Across each row
- Down each column
- For all numbers together

## How to Use

```python
from mean_var_std import calculate

# Example
result = calculate([0,1,2,3,4,5,6,7,8])
print(result)
```

If you try to use less than 9 numbers, you'll get an error message saying "List must contain nine numbers."

## Requirements
- Python 3
- NumPy

## Files Included
- `mean_var_std.py`: Contains the main calculator function
- `test_module.py`: Tests to verify the calculator works correctly
- `main.py`: Main file to run the tests

## Running Tests
```bash
python main.py
```

## Author
Aisha Umar Gama

## Acknowledgments
- Part of the FreeCodeCamp Data Analysis with Python Certification
