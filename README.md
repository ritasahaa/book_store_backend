# Book Store Backend

Book Store Backend is a RESTful API server built with Node.js, Express.js, and MongoDB. It provides backend services for managing books, user data, and database operations for the Book Store application.

## Features

* REST API Development
* Book Management APIs
* Database Integration with MongoDB
* Password Hashing using bcryptjs
* Environment Variable Configuration
* Cross-Origin Resource Sharing (CORS)
* Scalable Backend Architecture
* Error Handling and Validation

## Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* bcryptjs
* dotenv
* CORS

## Project Structure

```text
backend/
├── models
├── routes
├── controllers
├── config
├── middleware
├── index.js
└── package.json
```

## Installation

### Clone Repository

```bash
git clone https://github.com/ritasahaa/book-store-backend.git
```

### Install Dependencies

```bash
npm install
```

### Create Environment Variables

Create a `.env` file and add:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

### Run Server

```bash
npm start
```

## API Capabilities

* Retrieve Books
* Add New Books
* Update Existing Books
* Delete Books
* Database CRUD Operations

## Database

MongoDB is used as the primary database and Mongoose is used for schema modeling and database interactions.

## Future Enhancements

* JWT Authentication
* Role-Based Access Control
* Image Upload Support
* Book Reviews & Ratings
* Wishlist Management
* Admin Dashboard APIs

## Author

Rita Kumari Sah
