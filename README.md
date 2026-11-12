
# Python Exception Handling Assignment

## Description
This project demonstrates how to use Python's try and except statements to handle common errors and prevent programs from crashing.

The assignment contains three functions:

### 1. safe_divide(a, b)
- Divides one number by another.
- Handles ZeroDivisionError when the divisor is zero.
- Returns "Cannot divide by zero" when division by zero occurs.

### 2. safe_number(text)
- Converts text into an integer using int().
- Handles ValueError when the text cannot be converted.
- Returns "Not a number" when invalid input is provided.

### 3. get_field(learner, key)
- Retrieves a value from a dictionary using its key.
- Handles KeyError when the requested key does not exist.
- Returns "Field not found" when the key is missing.

## Concepts Covered
- Python functions
- try and except statements
- Error handling
- ZeroDivisionError
- ValueError
- KeyError
- Dictionary access
- Return statements

## How to Run the Program

1. Make sure Python is installed on your computer.
2. Open your terminal or command prompt.
3. Navigate to the folder containing your Python file.
4. Run the program using:

```bash
python filename.py
```

Replace filename.py with the actual name of your Python file.

## Expected Output

```text
5.0
Cannot divide by zero
42
Not a number
82
Field not found
```

## Author
PLP Student

## Conclusion
This assignment demonstrates how Python exception handling helps programmers identify and manage errors using try and except blocks.
