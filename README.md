# ALX Backend Python

This project focuses on using Python for backend development, specifically covering:

- Type annotations in Python 3
- Specifying function signatures and variable types with type annotations
- Duck typing
- Validating code with mypy

## Type Annotations in Python 3

Type annotations allow you to specify the expected data types of variables and function return values. This helps improve code readability and maintainability.

### Function Signatures and Variable Types

You can use type annotations to specify the types of function parameters and return values:

```python
def greet(name: str) -> str:
    return f"Hello, {name}!"

age: int = 25
```

### Duck Typing

Duck typing is a concept where the type or the class of an object is less important than the methods it defines. If an object implements the required methods, it can be used in place of another object.


### Validating Code with mypy

Mypy is a static type checker for Python. It checks the type annotations in your code and ensures that they are used correctly.

To install mypy:

```sh
pip install mypy
```

To run mypy on your code:

```sh
mypy your_script.py
```

This will validate the type annotations and report any type errors.
