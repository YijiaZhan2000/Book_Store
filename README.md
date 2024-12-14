# Book Store MERN Stack Project

This is a full-stack Book Store application built with the MERN stack (MongoDB, Express.js, React, Node.js). The app allows users to view, add, edit, and delete books, providing a simple CRUD interface with a beautiful user experience.

## Table of Contents

- [Project Setup](#project-setup)
- [Working Process](#working-process)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Links](#links)

---

## Project Setup

This project consists of both a backend (Node.js, Express.js, MongoDB) and a frontend (React, Vite, Tailwind CSS). Each part is developed and deployed separately.

### Backend (Node.js, Express, MongoDB)

The backend API handles CRUD operations for books and serves them to the frontend. It is built using:

- Node.js
- Express.js
- MongoDB with Mongoose
- CORS for cross-origin requests

### Frontend (React, Vite, Tailwind CSS)

The frontend is a single-page application (SPA) that provides a smooth user interface for interacting with the book data. It uses:

- React
- React Router DOM for navigation
- Tailwind CSS for styling
- Vite as the development server

---

## Working Process

Here’s how the development of this project was structured, step by step:

### Step 1: Set Up the Backend

1. **Create Node.js project from scratch**:
   - Initialized a Node.js project and installed necessary dependencies.

2. **Set up Express server**:
   - Created the first HTTP route to handle basic requests.
   - Integrated MongoDB and Mongoose to interact with the database.

3. **Develop CRUD API Endpoints**:
   - Created a Mongoose model for the Book entity.
   - Implemented API endpoints to:
     - Save a new book.
     - Fetch all books.
     - Get a book by ID.
     - Update a book.
     - Delete a book.

4. **Refactor Code for Clean Structure**:
   - Refactored the backend using Express Router for better organization.
   - Configured CORS to allow cross-origin requests from the frontend.

### Step 2: Set Up the Frontend

1. **Initialize React Project**:
   - Set up the frontend using React and Vite for fast development.
   - Applied Tailwind CSS for styling.

2. **Set up Routing**:
   - Implemented React Router DOM to handle navigation between different pages (e.g., Book List, Book Details, etc.).

3. **Display Books**:
   - Created a component to display a list of books fetched from the backend.
   - Designed the book list with Tailwind CSS for a clean and responsive UI.

4. **Add CRUD Functionality**:
   - Developed components to add, edit, and delete books:
     - Add book via a form.
     - Edit book details in a modal.
     - Delete book with confirmation.

5. **Improve UX/UI**:
   - Created reusable components (e.g., Book Card).
   - Designed a modal for adding books.
   - Improved the user experience with alert notifications and smooth transitions.

---

## Technologies Used

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - CORS

- **Frontend:**
  - React
  - React Router DOM
  - Vite
  - Tailwind CSS

---

## Installation

### Prerequisites

- Node.js
- MongoDB instance (local or cloud)
- NPM (Node Package Manager)

### Steps to Run the Backend

1. Clone the repository:  
   ```bash
   git clone <repo_url>
   cd backend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables (e.g., MongoDB connection string):
   - Create a `.env` file and add your MongoDB connection string.

4. Start the server:
   ```bash
   npm start
   ```

### Steps to Run the Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the React app:
   ```bash
   npm run dev
   ```

---

## Usage

- Open the backend API and frontend app in your browser.
- Use the frontend to add, view, edit, and delete books.
- The backend handles all the data storage and provides the API to the frontend.

---
