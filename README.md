
# Simple GUI Calculator

This is a simple calculator application built using Python's Tkinter library. It allows you to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Clear button to reset the input.
- User-friendly GUI.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/simple-gui-calculator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd simple-gui-calculator
    ```

### Running the Application

Run the following command to start the calculator:
```sh
python calculator.py
```

## Code Overview

The main components of the code are:

- **Global Variables:**
  - `expression`: A string that stores the current input expression.
  - `equation`: A Tkinter `StringVar` used to update the input field.

- **Functions:**
  - `press(num)`: Updates the expression with the pressed number or operator.
  - `equalpress()`: Evaluates the expression and updates the input field with the result.
  - `clear()`: Clears the input field.

- **Main Program:**
  - Sets up the Tkinter GUI window with buttons for digits, operators, equal sign, and clear function.
  - Arranges the buttons in a grid layout.

## GUI Layout

The GUI consists of the following components:
- An input field to display the current expression and result.
- Buttons for digits (0-9).
- Buttons for operators (+, -, *, /).
- Equal button (=) to evaluate the expression.
- Clear button to reset the input.
- Decimal button (.) to handle decimal numbers.

## Example Usage

1. Run the application.
2. Enter an arithmetic expression using the buttons.
3. Press the equal button (`=`) to see the result.
4. Use the clear button (`Clear`) to reset the input field.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Tkinter documentation and various online tutorials.
