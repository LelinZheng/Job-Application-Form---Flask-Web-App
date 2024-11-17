# Job Application Form - Flask Web App

This is a simple web application built with Flask, where users can submit a job application form. The form collects the following details:

- First Name
- Last Name
- Email
- Available Start Date
- Current Occupation

The application uses a SQLite database to store the submitted form data, and it provides flash messages upon successful form submission.

## Features

- **Form submission**: Users can submit their personal details through the form.
- **Flash messages**: Displays a success message when the form is submitted successfully.
- **SQLite database**: Stores form data in a local SQLite database (`data.db`).
- **Bootstrap 5**: Uses Bootstrap for responsive design.

## Technologies Used

- **Flask**: Python web framework for building the app.
- **SQLite**: Lightweight database for storing form data.
- **Bootstrap 5**: CSS framework for styling the form.
- **Jinja2**: Templating engine for rendering HTML in Flask.
- **Python 3.x**: Programming language used for backend logic.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/job-application-form.git
   cd job-application-form
