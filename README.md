# Email Validation in Python (Using String Functions)

This Python program validates email addresses using string functions. It checks if the email address entered by the user follows the standard email format.

## Usage

1. Enter an email address in the provided textbox.
2. Click the "Submit" button or press Enter.
3. The validator will check the email address format and display the validation result.

## Validation Rules

- The email address must contain at least 6 characters.
- The first character must be an alphabet.
- There must be only one "@" symbol.
- The domain part must end with ".com", ".org", etc.
- The username can contain letters (uppercase and lowercase), digits, underscores, dots, and "@" symbols.
- No spaces are allowed in the email address.

## Example

- Entering "example@email.com" will display "Email is valid."
![ Email Validation](/assets/valid.png)

- Entering "invalid.email@address" will display "Wrong email format. Please enter a valid email."

![ Email Validation](/assets/invalid.png)
## Getting Started

To run the email validator on your local machine, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/mustafaansarii/Email-Validation
   ```

2. Navigate to the project directory:

   ```bash
   cd EMAIL VALIDATION
   ```

3. Install the required dependencies:

   ```bash
   pip install gradio
   ```

4. Run the Python script:

   ```bash
   python Email Validation.py
   ```

5. Open your web browser and navigate to the provided URL.

## Customization

You can customize the validation rules or interface components by modifying the Python script (`validator.py`). You can add more complex validation logic or enhance the user interface as needed.
