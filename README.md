
# Book Management API

The Book Management API allows you to perform CRUD (Create, Read, Update, Delete) operations on books. It's built using Node.js and MongoDB for storing book data.

## API Endpoints and Usage

### Create a New Book
- **Endpoint:** `POST /books`
- **Usage:** Create a new book by providing the book's title, author, and summary in the request body.
- **Request Example:**
  ```json
  {
    "title": "The Great Gatsby",
    "author": "F. Scott Fitzgerald",
    "summary": "A summary of the book goes here."
  }
