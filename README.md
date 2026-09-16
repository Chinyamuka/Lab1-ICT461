# Course Registration Form

A simple, responsive, and modern **Course Registration Form** built using HTML, CSS, and JavaScript.

## Features

* Responsive design for desktop and mobile devices
* Centered registration form
* Clean and modern user interface
* Full name validation
* Student ID format validation
* Programme selection
* Course selection
* Required-field validation
* Custom error messages
* Interactive input focus effects
* Submit button hover animation
* Client-side form validation using JavaScript

## Student ID Format

The Student ID must follow this format:

```text
STU-2025-001
```

The format requires:

* 3 letters
* A hyphen
* 4 digits
* A hyphen
* 3 digits

### Example

```text
STU-2025-001
```

## Available Programmes

The form currently provides the following programmes:

* Computer Science
* Data Science
* Electrical Engineering
* Business Administration

## Available Courses

The available courses are:

* CS101 – Intro to Programming
* CS205 – Data Structures
* DS501 – Machine Learning
* EE210 – Circuit Analysis

## Technologies Used

* **HTML5** — Structure of the form
* **CSS3** — Styling, layout, responsiveness, and animations
* **JavaScript** — Form validation and submission handling

## Project Structure

```text
course-registration/
│
├── index.html
└── README.md
```

## How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in a web browser.

Alternatively, use **Visual Studio Code with Live Server** to run the project.

## Form Validation

The form uses HTML5 validation to ensure that:

* Full Name contains at least two characters.
* Student ID follows the required format.
* A programme is selected.
* A course is selected.
* Required fields are completed before submission.

JavaScript also checks the form before displaying a successful submission message.

## Current Limitation

This is currently a **frontend demonstration**. The form does not store registration information in a database or send the information to a backend server.

The following line:

```html
<form action="#" method="post">
```
