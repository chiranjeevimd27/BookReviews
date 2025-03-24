# Book Review Platform

## Objective
The **Book Review Platform** allows users to browse books, read and write reviews, and rate books. The application consists of a **React** frontend and a **Node.js** backend using **Express** and **SQL/MongoDB** for data persistence.

## Features
### **Frontend (React)**
- Responsive UI with the following pages:
  - **Home Page**: Displays featured books
  - **Book Listing Page**: Search and filter books
  - **Individual Book Page**: Book details and user reviews
  - **User Profile Page**: View and update user information
  - **Review Submission Form**: Users can write and submit reviews
- Implements **state management** using Redux or React Context
- Uses **React Router** for navigation
- Integrates with backend API
- Implements **error handling** and **loading states**

### **Backend (Node.js, Express, SQL/MongoDB)**
- RESTful API with the following endpoints:
  - `GET /books` - Retrieve all books (pagination supported)
  - `GET /books/:id` - Retrieve a specific book
  - `POST /books` - Add a new book (**admin only**)
  - `GET /reviews` - Retrieve reviews for a book
  - `POST /reviews` - Submit a new review
  - `GET /users/:id` - Retrieve user profile
  - `PUT /users/:id` - Update user profile
- Implements **data validation** and **error handling**
- Uses **SQL/MongoDB** for data persistence

## **Installation and Setup**
### **Prerequisites**
Ensure you have the following installed:
- Node.js
- npm or yarn
- MongoDB (if using MongoDB)
- MySQL/PostgreSQL (if using SQL)

### **Clone the Repository**
```sh
git clone https://github.com/yourusername/book-review-platform.git
cd book-review-platform
```

### **Backend Setup**
1. Navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and configure database credentials.
4. Run the server:
   ```sh
   npm start
   ```

### **Frontend Setup**
1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React app:
   ```sh
   npm start
   ```

## **API Documentation**
The API follows RESTful principles. Below is a sample request to fetch all books:
```sh
GET /books
```
Response:
```json
[
  {
    "id": 1,
    "title": "The Great Gatsby",
    "author": "F. Scott Fitzgerald",
    "rating": 4.5
  }
]
```

## **Evaluation Criteria**
- Code quality and organization
- Proper use of React hooks and components
- RESTful API design and implementation
- Database schema design
- Error handling and edge case management
- UI/UX design considerations
- Documentation clarity



