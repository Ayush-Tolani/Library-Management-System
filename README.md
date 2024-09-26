# Library-Management-System
Overview
The Library Management System (LMS) is a Python-based application designed to manage a library's book records. It allows users to display available books, issue books, return books, and add new books to the library.

Features
Display Books: Lists all available books with their status.
Issue Books: Allows users to borrow books by entering the book ID.
Return Books: Users can return books they have borrowed.
Add Books: Users can add new books to the library collection.
Requirements
Python 3.x
Basic text file for storing book titles (list_of_book.txt)
Getting Started
Clone the repository (or download the files).
Create a text file named list_of_book.txt in the same directory as the Python script. Add the titles of the books, each on a new line.
Run the application using Python:
bash
Copy code
python lms.py
Usage
Upon running the program, users will see a menu with the following options:

D: Display Books
I: Issue Books
A: Add Books
R: Return Books
Q: Quit
Users can press the corresponding key to perform the desired action.

Example
To display the list of books, press D.
To issue a book, press I, enter the book ID, and provide your name.
To return a book, press R and enter the book ID.
To add a new book, press A and enter the book title.
Code Structure
LMS Class: Contains all the functionalities related to the library management system.
__init__(): Initializes the library and loads books from a text file.
display_books(): Displays the list of books.
issue_books(): Handles the book issuing process.
return_book(): Handles the book returning process.
add_book(): Allows users to add new books to the library.
Contributing
Feel free to fork the repository and submit pull requests for any enhancements or bug fixes.
