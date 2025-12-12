# AddTwo

A lightweight Python package designed to simplify the process of adding two numbers.

## Features

- **Simple API**: A single function `add(a, b)` to get the job done.
- **Type Checking**: Ensures inputs are numeric (int or float) and raises informative errors if not.
- **CLI Support**: Execute addition directly from the command line.

## Installation

You can install `AddTwo` via pip:

```bash
pip install addtwo-Monu
```

*(Note: Replace `addtwo-Monu` with the exact package name if different on PyPI)*

## Usage

### python

Import the library in your Python scripts:

```python
from addtwo import add

result = add(5, 7)
print(f"The sum is: {result}")  # Output: The sum is: 12
```

### Command Line Interface (CLI)

You can also use the package directly from your terminal:

```bash
addtwo 10 25.5
# Output: 35.5
```

## Functions

### `add(a, b)`

Returns the sum of `a` and `b`.

*   **Parameters**:
    *   `a` (int | float): First number.
    *   `b` (int | float): Second number.
*   **Returns**: (int | float) The sum of `a` and `b`.
*   **Raises**: `TypeError` if inputs are not numbers.
