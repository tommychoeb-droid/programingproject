Community Database

Overview

The Community Database is a Graphical User Interface (GUI) desktop application developed using Python and Tkinter. The system was designed to manage community resident information electronically and provide an efficient alternative to manual record keeping.

The application enables users to add, search, delete, display, and analyze resident records through a simple and user-friendly interface.


Problem Statement

Many communities still rely on paper-based methods to store resident information. Such methods are prone to:

- Loss of records
- Difficulty in searching for information
- Data duplication
- Time-consuming updates
- Human errors

This project addresses these challenges by providing a computerized management system.


Features

The system provides the following features:

- Add Resident Record
- Search Resident by Resident ID
- Delete Resident Record
- View All Resident Records
- Generate Community Statistics
- Clear Input Fields
- Error Handling and Input Validation


Input Validation

The system validates user input using error messages.

Validation rules include:

- Resident ID must contain numbers only.
- Full Name must contain letters and spaces only.
- Age must be numeric and greater than zero.
- Gender must contain letters only.
- Occupation must contain letters and spaces only.
- Phone Number must contain digits only.
- Duplicate Resident IDs are not allowed.


Technologies Used

- Python 3
- Tkinter
- Messagebox Module


Structured Programming Concepts Applied

This project demonstrates:

- Functions
- Lists
- Dictionaries
- Conditional Statements
- Loops
- Input Validation
- Event-Driven Programming
- GUI Design


Data Structure

Resident records are stored using a list of dictionaries.

Example:

resident = {

    "ID": "101",

    "Name": "Tommy",

    "Age": 20,

    "Gender": "Male",

    "Occupation": "Student",

    "Phone": "076123456",

    "Address": "Freetown"

}


Sustainable Development Goal (SDG)

This project primarily supports:

SDG 16 – Peace, Justice and Strong Institutions

The system promotes:

- Efficient community administration
- Accurate record keeping
- Transparency in information management
- Better accessibility of community data

The project also contributes to:

SDG 9 – Industry, Innovation and Infrastructure

through the application of information technology to modernize community services.


Future Improvements

Possible future enhancements include:

- SQLite Database Integration
- CSV Import and Export
- Update Record Function
- Password Authentication
- User Login System
- Report Generation


Author

Name: Tommy-Choe Bachalle-Taylor

Project: Community Data Management System

Language: Python

GUI Library: Tkinter

Year: 2026


License

This project is licensed under the MIT License.
