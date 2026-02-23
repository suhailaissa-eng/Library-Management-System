# Library-Management-System


## Project Description
This is a Library Management System that allows users to:
- View, add, edit, and delete books
- Borrow books and track return dates
- Create collections of books
- Register users with different roles (Admin/User)

## Technologies Used
- **Frontend:** Angular, HTML, CSS
- **Backend:** Java, Spring Boot, REST APIs
- **Database:** PostgreSQL
- **HTTP:** Angular HttpClient for API communication


## Features
- **Books Management**
  - Display list of books with title, author, year, category, and cover image
  - Add new books
  - Edit and delete existing books
  - Search and filter books by author or category

- **User Management**
  - User registration and login
  - Role-based access (Admin/User)
  - Users can borrow books

- **Borrowing System**
  - Track borrowed books with borrow date and return date
  - Display list of borrowed books per user

- **Collections**
  - Create and manage collections of books
  - Add or remove books from collections


## API Endpoints
- `GET /books` → Get all books
- `POST /books` → Add a new book
- `PUT /books/:id` → Update a book
- `DELETE /books/:id` → Delete a book
- `POST /users/register` → Register a new user
- `POST /users/login` → User login
- `GET /users/:id/borrowed` → Get borrowed books for a user

## Database Structure
- **Users:** id, name, email, password(hashed), role
- **Books:** id, title, author, year, category, cover_image
- **BorrowedBooks:** id, user_id, book_id, borrow_date, return_date
- **Collections:** id, name, description
- **CollectionBooks:** collection_id, book_id 



Suhaila Issa
