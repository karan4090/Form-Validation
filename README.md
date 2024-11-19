# Form-Validation

# Explanation
HTML Structure:

The form includes input fields for name, email, and password, each with associated error messages (.error-message).
Error messages are initially hidden using display: none.
CSS Styling:

Inputs have subtle borders, padding, and a responsive design.
Error messages are styled in red and appear dynamically when validation fails.
JavaScript Code:

Real-Time Validation:
Event listeners (input event) validate fields as the user types.
Error messages appear if validation fails and disappear when corrected.
Validation Functions:
validateName: Ensures the name field is not empty.
validateEmail: Uses a regex to validate the email format.
validatePassword: Checks if the password is at least 8 characters.
Form Submission:
The submit event listener prevents form submission if any field is invalid and displays an alert.
Real-Time Feedback:

As the user types, errors are displayed or removed instantly.
This improves the user experience by guiding the user toward valid input.
Workflow
Name Validation:

Leave the name field empty → Error message appears: "Name is required."
Type any text → Error message disappears.
Email Validation:

Enter an invalid email (e.g., user@domain) → Error message: "Please enter a valid email."
Enter a valid email (e.g., user@domain.com) → Error message disappears.
Password Validation:

Enter fewer than 8 characters → Error message: "Password must be at least 8 characters long."
Enter 8 or more characters → Error message disappears.
Form Submission:

If any field is invalid, the form will not submit, and the user is prompted to fix errors.
This implementation ensures a clean, interactive form validation process and enhances usability with real-time feedback.
