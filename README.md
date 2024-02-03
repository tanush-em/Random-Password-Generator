# Random Password Generator

This simple web-based random password generator allows you to create strong and secure passwords tailored to your preferences. You can customize the password length and include uppercase letters, lowercase letters, numbers, and symbols based on your security requirements.

## Getting Started

To use the random password generator, follow these steps:

1. Open the HTML file in your preferred web browser.
2. Adjust the password length using the "Length" input field.
3. Choose the character types you want to include in your password by checking the corresponding checkboxes for uppercase letters, lowercase letters, numbers, and symbols.
4. Click the "Generate" button to create a random password.
5. Optionally, you can click the "Copy" button to copy the generated password to your clipboard.

## Code Reference

The JavaScript code provided implements the functionality of the random password generator. Here's a quick overview of the key components:

- `password_el`: Represents the HTML element where the generated password will be displayed.
- `length_el`: Represents the HTML input element for specifying the password length.
- `uppercase_el`, `lowercase_el`, `numbers_el`, `symbols_el`: Represent the HTML checkboxes for including uppercase letters, lowercase letters, numbers, and symbols, respectively.
- `generate_btn`: Represents the "Generate" button, and `copy_btn`: Represents the "Copy" button.
- `GeneratePassword()`: Function responsible for generating a random password based on user preferences.
- `CopyPassword()`: Async function to copy the generated password to the clipboard using the `navigator.clipboard` API.

Feel free to customize the code or integrate it into your project as needed.


## Acknowledgments

Special thanks to the original code reference that served as the foundation for this project. The random password generator was created to provide a simple and efficient tool for generating secure passwords. If you have any suggestions or find issues, please feel free to contribute to the project.

Happy password generating! 🌐🔐
