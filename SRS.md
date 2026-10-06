**1.Basic SRS**
**1.Introduction**
Purpose
The purpose of the Library App is to provide a simple digital system for managing library books and borrowing activities.
**Intended Users**
Students
Library users
Librarians
Administrators
**2 System Features**
User Module
Login
Search books
View book details
Borrow books
Return books
Librarian Module
Add books
Update book information
Remove books
View borrowing records
**3 System Requirements**

**Input:**

Username and password
Book title/author/category
Book details
Borrow/return information

**Processing:**

Validate user login
Search books
Check book availability
Update borrowing status
Update book records
**Output:**

Login status
Search results
Book availability
Borrowing confirmation
Return confirmation
 **2.User Stories and Acceptance Criteria**
US 1 – User Login

User Story:

As a library user, I want to log in so that I can access the library system.

Acceptance Criteria
User can enter username and password.
Valid credentials allow access.
Invalid credentials display an error message.
Unauthorized users cannot access protected features.

Priority: High

US 2 – Search Books

User Story:

As a library user, I want to search for books so that I can easily find the book I need.

Acceptance Criteria
User can enter a book title, author, or category.
Matching books are displayed.
Book availability is shown.
If no book is found, an appropriate message is displayed.

Priority: High

US 3 – Borrow Books

User Story:

As a library user, I want to borrow an available book so that I can read it.

Acceptance Criteria
User can select an available book.
The system confirms the borrowing.
The book status changes to unavailable/borrowed.
Borrowing information is recorded.

Priority: High

US 4 – Return Books

User Story:

As a library user, I want to return a borrowed book so that it becomes available to other users.

Acceptance Criteria
User can view borrowed books.
User can select a book to return.
The system records the return.
The book becomes available again.

Priority: Medium

US 5 – Manage Books

User Story:

As a librarian, I want to manage books so that the library catalogue remains updated.

Acceptance Criteria
Librarian can add a new book.
Librarian can update book details.
Librarian can remove a book.
Updated information is reflected in the catalogue.

Priority: Medium
