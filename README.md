# Python

Simple program to add two numbers:

```python
def add_numbers(first: float, second: float) -> float:
    """Return the sum of two numbers."""
    return first + second


def main() -> None:
    try:
        first = float(input("Enter the first number: "))
        second = float(input("Enter the second number: "))
    except ValueError:
        print("Please enter valid numeric values.")
        return

    total = add_numbers(first, second)
    print(f"The sum of {first} and {second} is {total}")


if __name__ == "__main__":
    main()
```
