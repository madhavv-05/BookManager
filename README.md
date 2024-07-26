# Project Overview
This project is a Python application that allows users to manage a books database through a graphical user interface (GUI) built with Tkinter. 
Users can add, update, delete, and view books stored in a MySQL database. The project uses MySQL Workbench for database management, and database credentials are stored in a separate configuration file.

## Project Structure
dbconfig.py       # Contains database credentials
mybooks.py        # Main GUI application
sql.txt           # SQL query to create the database and table
README.md         # Project documentation


### File Descriptions
dbconfig.py: Contains the database credentials needed to connect to the MySQL database. Ensure this file is updated with your specific database details.
sql.txt: SQL script to create the database and table required for the application. Run this script in MySQL Workbench.
mybooks.py: The main Python script that creates the GUI using Tkinter. It includes functionality to add, update, delete, and view books in the database.


#### Usage
Add Book: Enter the book details in the text fields and click the "Add" button.
Update Book: Select a book from the list, edit the details, and click the "Update" button.
Delete Book: Select a book from the list and click the "Delete" button.
View Books: All books are displayed in the listbox on the GUI.

