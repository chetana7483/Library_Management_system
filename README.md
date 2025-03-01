Library Management System

Overview
The Library Management System is a command-line application built with Python and MongoDB, allowing users to efficiently manage books by adding, viewing, updating, deleting, borrowing, and returning them.

Prerequisites
To use this system, ensure Python 3.x and MongoDB are installed. Install the required dependencies with:
pip install pymongo

Setup & Usage
Clone the repository, navigate to the project directory, start MongoDB, and run the application:
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
mongod
python library_management.py
Follow the interactive menu to perform book management operations.

Database Structure
The system uses LibraryDB, containing two collections: Books, which stores book details like title, author, year, and copies, and Users, which tracks borrowed books with user names, book titles, and borrow dates.
Contributing
Contributions are welcome! Fork the repository and submit pull requests.

License
This project is licensed under the MIT License.
