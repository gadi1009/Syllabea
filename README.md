Syllabea - Final Project - Software Engineering
Netanel Shen - natidd
Gadi Yohanan - gadi1009
Mhdi Janam
Bakar abu salim
--------

Syllabea is a web-based system for managing course syllabi. It is built using the Go programming language with HTML templates and HTMX for dynamic web features. The system helps lecturers and managers create, edit, and view syllabi.

Features
--------

- Lecturers can create, edit, and save their syllabi.
- Managers can see and manage all syllabi in the system.
- The system keeps track of progress through a sidebar that shows how complete the syllabus is.
- Uses HTMX for updating parts of the page without reloading the whole page.
- Uses Go templates to create simple and fast web pages.

Technologies Used
-----------------

- Go (backend)
- HTMX (for dynamic interactions)
- HTML and CSS (for the frontend)
- MySQL (for the database)

Roles
-----

- Lecturer: Can only see and edit their own syllabi.
- Manager: Can see and manage all syllabi.

Run Syllabea locally with Go (no Docker)
----------

# 1. Go to the project folder
cd ~/xxxxxxx/Syllabea-master

# 2. Initialize Go modules (if not already)
go mod tidy

# 3. Run the app
go run main.go
Listening on http://localhost:8080

Future Plans
------------

- Add support for more user roles.
- Allow exporting syllabi to PDF.
- Improve the design and user experience.
