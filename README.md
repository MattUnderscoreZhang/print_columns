A simple package for printing text to the terminal in columns

# Example

```python
from print_columns import print_columns


if __name__ == "__main__":
    lorem_ipsum = "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
    value = 3
    notes = "This is Lorem Ipsum. It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout."

    print_columns(
        string=[lorem_ipsum, str(value), notes],
        column_widths=[50, 2, 50],
        colors=["red", "green", "blue"],
    )
```

The output looks like this:
![alt text](https://github.com/MattUnderscoreZhang/print_columns/blob/main/examples/screenshot.png?raw=true)

See the examples/ folder for more.
