# React Form Application

This project is a simple React application that demonstrates how to create and manage a form with various input fields, including text inputs, radio buttons, checkboxes, file upload, URL input, a dropdown select, and a textarea. The application also includes functionalities for form submission and resetting the form inputs.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Form Fields](#form-fields)
- [State Management](#state-management)
- [Contributing](#contributing)


## Features

- Manage form state using React hooks (`useState`).
- Validate required fields.
- Handle form submission and reset.
- Toggle checkbox states.
- Upload files and handle file inputs.
- Use a dropdown select with optgroups.
- Include a textarea for additional information.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/react-form-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd react-form-app
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm start
    ```

The application will be available at `http://localhost:3000`.

## Usage

To use the form application, follow these steps:

1. Fill in the form fields with the required information.
2. Click the "Submit" button to log the form data to the console.
3. Click the "Reset" button to clear all form fields and reset them to their initial values.

## Form Fields

The form includes the following fields:

- **First Name**: Text input for the user's first name (required).
- **Last Name**: Text input for the user's last name (required).
- **Email**: Email input for the user's email address (required).
- **Contact**: Telephone input for the user's contact number (required).
- **Gender**: Radio buttons to select the user's gender (male, female, other) (required).
- **Subjects**: Checkboxes to select the user's best subjects (English, Maths, Physics).
- **Resume**: File input to upload the user's resume (required).
- **URL**: URL input for the user's website or profile link (required).
- **Select Your Choice**: Dropdown select to choose a preferred technology.
- **About**: Textarea for the user to provide additional information about themselves (required).

## State Management

The application uses React's `useState` hook to manage the state of each form field. Here's a brief overview of the state variables:

- `firstName`, `lastName`, `email`, `contact`, `gender`: State variables for text inputs and radio buttons.
- `subjects`: State variable for managing the state of checkboxes.
- `resume`: State variable for the file input.
- `url`: State variable for the URL input.
- `selectedOption`: State variable for the dropdown select.
- `about`: State variable for the textarea.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:

    ```bash
    git checkout -b feature-branch
    ```

3. Make your changes.
4. Commit your changes:

    ```bash
    git commit -m "Add new feature"
    ```

5. Push to the branch:

    ```bash
    git push origin feature-branch
    ```

6. Open a pull request.

