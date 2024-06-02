## Library Management System Project in C++

### Project Overview

This project is a comprehensive Library Management System designed using Object-Oriented Programming (OOP) principles in C++. It performs various tasks to manage user authentication, student membership, book issuance, and notifications effectively.

### Key Features

1. **User Registration and Authentication**:
   - Takes username and password from new users and stores them in a file-based system.
   - Validates username and password from the file-based system for returning users attempting to log in.

2. **Student Membership Management**:
   - Adds new students to the library membership.
   - Stores student details such as name, ID, books issued, and issue dates.

3. **Book Issuance and Returns**:
   - Allows students to issue books from the library.
   - Updates the records to remove books returned to the library.

4. **Notifications**:
   - Provides notifications regarding the return deadlines for checked-out books.

5. **Student Information Display**:
   - Displays all details of all students with a simple key press.
   - Displays login credentials after logging in.

6. **Password Management**:
   - Enables users to change their password.

7. **Portal Exit**:
   - Allows users to exit the portal at any time.

### Project Implementation

This project utilizes several key programming concepts and techniques:

- **Object-Oriented Programming**: Core functionality is built around OOP concepts, encapsulating data and functions within classes.
- **File Handling**: User data and library records are stored and retrieved from files.
- **Regular Expressions**: Utilized for input validation, such as ensuring the correctness of usernames and passwords.
- **Array Handling**: Arrays are used to manage collections of books and student records.
- **Time Module**: Manages book issue and return dates, ensuring accurate notifications.
- **Modular Approach**: The code is organized into modules for better readability and maintainability.

### Usage

The system is designed to be user-friendly and intuitive, providing a seamless experience for both librarians and students.

1. **Registration**: New users can register by providing a username and password, which are securely stored.
2. **Login**: Returning users can log in by entering their credentials, which are validated against stored records.
3. **Membership Management**: Librarians can add new students to the membership database.
4. **Book Management**: Students can issue and return books, with the system updating records accordingly.
5. **Notifications**: The system notifies users about the return deadlines for issued books.
6. **Information Display**: Users can view all student details and their own login credentials easily.
7. **Password Change**: Users can change their password if needed.
8. **Exit**: Users can exit the system at any point.

This project demonstrates a robust implementation of a Library Management System using C++, incorporating essential programming techniques and principles.

---
