# Project-1

# Client-Side Signup Form Validation

This repository contains a simple signup form implemented using HTML, CSS, and JavaScript.  
The application performs client-side validation in real time and prevents form submission until all inputs meet defined validation rules.

---

## Purpose

The purpose of this project is to demonstrate:
- Basic frontend form handling
- Real-time validation using JavaScript
- DOM manipulation without external libraries
- Clean and maintainable UI logic

---

## Functional Description

The form consists of three input fields: name, email, and password.  
Validation logic is executed on every input event.  
If any field is invalid, an inline error message is displayed and the submit button remains disabled.

On successful validation, the form can be submitted and a confirmation message is shown.

---

## Validation Criteria

- **Name**: Must contain at least 3 non-whitespace characters
- **Email**: Must include the `@` symbol
- **Password**: Must contain at least 6 characters
- **Submission**: Disabled unless all conditions are satisfied

---

## Technology Stack

- HTML5 for structure
- CSS3 for layout and styling
- JavaScript (ES6) for validation logic and event handling

No third-party libraries or frameworks are used.

---

## File Structure