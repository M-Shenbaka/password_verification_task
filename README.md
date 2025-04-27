# Password Verification Form

This project is a simple password verification form where users are required to enter a username, password, and re-type the password for confirmation. The form performs validation checks to ensure the input is correct and provides real-time feedback on any errors.

# Features

Username Validation: Ensures that the username field is not empty and contains only letters (both upper and lower case).

Password Validation: Verifies that the password is at least 6 characters long, contains both uppercase and lowercase letters, and includes at least one number.

Re-type Password Validation: Ensures the re-typed password matches the original password entered by the user.

Error Messages: Provides helpful error messages for invalid inputs, such as empty fields or incorrect formats.

Success Message: If all validations pass, a success message is displayed upon form submission.

# Technologies Used

HTML: Structure of the form, including input fields and labels.

CSS: Styling to make the form visually appealing and centered on the screen.

JavaScript: Form validation logic to ensure inputs meet the required criteria.

# Installation

To use this form locally:

Copy the HTML and save it as a .html file, for example, index.html.

Open the file in any browser to see the form in action.

# How It Works

Username Field: The username must only contain alphabetic characters (both uppercase and lowercase). An error is displayed if the field is empty or contains non-alphabetical characters.

Password Field: The password must be at least 6 characters long and include at least one lowercase letter, one uppercase letter, and one number. The field cannot be left empty.

Re-type Password Field: The re-typed password must exactly match the original password. If the passwords do not match, an error message is displayed.

Form Submission: Once all fields are valid, an alert is displayed indicating a successful form submission. The form is then reset.
