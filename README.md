# Calculator with GUI

This is a simple **Calculator Application** built using Python's `tkinter` library. The calculator provides basic arithmetic functionalities with an intuitive graphical user interface (GUI).

---

## Features

- **Basic Operations**: Addition, Subtraction, Multiplication, and Division.
- **Additional Functionalities**:
  - **Clear (AC)**: Reset the input.
  - **Sign Toggle (∓)**: Change the sign of the current number.
  - **Percentage (%)**: Compute the percentage value.
- **Error Handling**: Displays `Error` for invalid calculations.
- **Responsive Design**: Neatly arranged buttons for easy interaction.

---

## Installation

1. Clone this repository or download the source code
2. Ensure you have Python 3.x installed. You can download it from [python.org](python.org).
3. Install the required libraries (if any).

## How It Works

- **Design :** The GUI is created using `tkinter`. It includes a grid of buttons for digits, operators, and functions.
- **Logic :** User input is managed using event listeners attached to buttons. Calculations are processed using Python's `eval` function with safeguards for invalid inputs.

## Customization

- **Themes :** Modify button colors and fonts in the `InputForm` class.
- **Icon :** Replace `ICON.ico` with your desired icon file.
- **Window Size**: Adjust dimensions in the `self.geometry` line in the `Application` class.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to enhance the functionality or improve the design.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author

Developed by **Rohit Malwal**<br>
Feel free to reach out for suggestions or improvements! 😊
