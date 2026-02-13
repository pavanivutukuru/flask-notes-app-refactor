# Flask Notes App (Refactored)

##  Project Overview
This is a simple Notes Web Application built using Flask.
The project was given as a debugging and refactoring task.

The original code had routing and form-handling issues which were identified and fixed.

---

##  Bugs Identified

1. Route allowed only POST method, causing 405 Method Not Allowed error on page load.
2. Used `request.args.get()` instead of `request.form.get()` for POST data.
3. Form did not specify method="POST".
4. No validation to prevent empty notes from being stored.

---

##  Fixes Implemented

- Added support for both GET and POST methods.
- Corrected form data handling using `request.form.get()`.
- Added input validation to prevent empty submissions.
- Improved project structure.

---

##  Features

- Add notes dynamically
- Input validation
- Proper HTTP method handling
- Clean project structure

---

##  Technologies Used

- Python
- Flask
- HTML

---

##  How to Run the Project

1. Clone the repository
2. Create virtual environment:
