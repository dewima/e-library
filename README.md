# e-library
project SQL
# Database Specification:
* Purpose
* Business Rules
* Design Requirements
* Design Decisions
* ERD diagram
# Database Purpose:
* Manage book collections in each managed library
* Make it easy for users to access the e-library either to borrow or hold books
* Manage user transactions for borrowing and returning books
# Business Rule:

- **Manage Multiple Libraries:**
  - The app manages multiple libraries, each housing a diverse collection of books with varying amounts available for borrowing.

- **Book Collection:**
  - The database needs to store information about the various book collections, including titles, authors, and quantities available.
  - To facilitate user searches, books are also divided into categories such as personal development, biography, Fantasy, Romance, Science Fiction, etc.

- **User Registration:**
  - Users can register on the e-library platform.
  - Registered users can interact with the platform by borrowing books, placing holds, and managing their accounts.

- **Loan and Hold System:**
  - Users can borrow books from any library on this app if the books are available.
  - The loan period is 2 weeks. Users can return books earlier than the deadline.
  - Books will be returned automatically if they exceed the time limit.
  - Users can only borrow 2 books at a time.
  - The platform tracks loan transactions, including loan date, due date, and return date.
  - Users can freeze books that are not currently available.
  - The library maintains a hold queue, and when a book becomes available, it can be borrowed by customers at the front of the queue.
  - If a customer does not borrow a stored book within one week, the book is released for borrowing by another user.
  - Users can only store 2 books simultaneously.
# Desaign Requirements
* designing the database schema
* ensure that the relationships between tables are well defined and foreign keys are used appropriately. 
* Include any additional attributes or tables required to support the functionality described.
* The design should reflect a comprehensive understanding of the e-library requirements and provide an effective solution for managing books, holds and loans in a multi-library environment.
# ERD
![Uploading e-library project ERD.png…]()

