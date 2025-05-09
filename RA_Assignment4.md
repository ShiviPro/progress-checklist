# RA_Assignment4

## Global State:
- [x] Use useContext to create a BookContext for managing the global state of books.

_Please Note: BookContext is only created & scoped right now. There is no consumption logic implemented till now._

## Features:
### Add Books:
- [ ] Create a form to add a book with the following details:
  - Title
  - Author
  - Status (Read/Unread)

### View Books:
- [ ] Display a list of all books in the library.
- [ ] Each book should display its title, author, and status (Read/Unread).
- [ ] Mark as Read/Unread:
- [ ] Provide a toggle button for each book to mark it as "Read" or "Unread".

### Delete Books:
- [ ] Provide a delete button to remove books from the library.

### Filter Books:
Create 3 pills/buttons to filter books by their status:
  - [ ] All Books (count): To show all books.
  - [ ] Read Books (count): To show only books marked as "Read".
  - [ ] Unread Books (count): To show only books marked as "Unread". 

### Navigation:
Use React Router to create separate routes:
  - [x] AllBooks: Displays the list of all books.
  - [x] AddBook: Displays the form to add a new book.

![image](https://github.com/user-attachments/assets/4084c431-cfdb-4411-9ec8-e767ba22193f)

_Please Note: Only the skeleton of these pages has been created till now._

### Data Persistence:
Use localStorage to save the books so that they persist even after refreshing the page or closing the browser.
  - [ ] Load books from localStorage when the app starts.
  - [ ] Save any changes (add, update, delete) to localStorage.
