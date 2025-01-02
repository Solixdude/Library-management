Library Management System

This Python program is a simple Library Management System that allows users to manage books by providing functionalities such as displaying available books, lending books, adding new books, and returning books. The system reads books from a database file and interacts with users through a command-line interface.
Features
1. Display Books

    Lists all the books available in the library.
    Provides a clear view of the library's inventory.

2. Lend a Book

    Allows a user to borrow a book.
    Keeps track of which user has borrowed which book.
    Prevents lending a book if it is already borrowed.

3. Add a Book

    Enables the addition of new books to the library.
    Updates both the in-memory book list and the external database file.
    Checks for duplicates to avoid adding the same book multiple times.

4. Return a Book

    Allows a user to return a previously borrowed book.
    Updates the lending database accordingly.

Program Flow

    The program initializes by reading a list of books from an external database file (specified by the user).
    Users interact with the system via a menu offering four main options:
        Display available books.
        Lend a book.
        Add a new book.
        Return a book.
    Users can exit the program by selecting the quit option.
