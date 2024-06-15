# Library Management System (C)

This is a command-line based Library Management System project developed in C programming language. It provides functionality for managing book details, including adding new books, displaying category-wise lists, calculating category-wise total and average book costs, displaying book details by number, deleting books, and clearing all book details. The book details are stored in a binary file for persistent storage.

## Features

- Add new books with input validation for book number, title, author, number of pages, category, and cost
- Display a category-wise list of books (Fictional, Physics, History)
- Calculate and display the category-wise total and average book cost
- Display detailed information of a book by its book number
- Delete a book by its book number
- Clear all book details
- Save and load book details from a binary file

## Requirements

- A C compiler (e.g., GCC) to compile and run the program.

## Usage

1. Compile the `project15.c` file using a C compiler.
2. Run the compiled executable.
3. The program will display a menu with various options.
4. Select the desired option by entering the corresponding number.
5. Follow the on-screen instructions for each option.
6. To exit the program, select the "Exit" option (7) from the menu.

Note: The book details are stored in a binary file named `booklibrary.bin` in the same directory as the executable. The file will be created automatically if it doesn't exist.
