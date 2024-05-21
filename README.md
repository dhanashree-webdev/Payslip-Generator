# Payslip Generator

The Payslip Generator is a simple and efficient tool to generate payslips. This project provides an easy-to-use interface where users can generate payslips by simply clicking on the executable file. 

## Features

- **Simple Execution:** Run the application with a single click on the executable file.
- **Customizable Layout:** Modify the payslip layout through the provided HTML file.
- **Easy Field Management:** Add or remove fields by making changes directly in the Python code.

## How to Use

1. **Run the Application:**
   - Click on the executable file to start the Payslip Generator.

2. **Customize Layout:**
   - To change the layout of the payslip, edit the HTML file provided in the project.

3. **Modify Fields:**
   - To add or remove fields, make the necessary changes in the Python code.

## Installation

To install and set up the Payslip Generator, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/dhanashree-webdev/payslip-generator.git
   cd payslip-generator
   ```

2. **Set Up Virtual Environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Generate Executable:**
   ```bash
   pyinstaller -w -n "aetos payslip" aetos.py
   ```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to submit a pull request or open an issue.

## Author

Created by [@dhanashreemhatre](https://github.com/dhanashreemhatre).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
