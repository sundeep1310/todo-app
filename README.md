# Todo Application with React and Redux

A simple Todo application built with React and Redux that allows users to manage todo items and view employee data.

## Features

- Add new todo items
- Display list of todo items
- Delete existing todo items
- Update todo items
- View employee list from external API
- Multiple route navigation

## Technologies Used

- React (Functional Components & Hooks)
- Redux & Redux Thunk (State Management)
- React Router (Navigation)
- Axios (API calls)

## Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v14 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone <https://github.com/sundeep1310/todo-app.git>
```

2. Navigate to the project directory:
```bash
cd todo-application
```

3. Install dependencies:
```bash
npm install
```

## Running the Application

To start the development server:
```bash
npm start
```

The application will open in your default browser at `http://localhost:3000`

## Application Structure

The application consists of two main routes:
1. Todo List (/todos)
   - View all todos
   - Add new todos
   - Delete existing todos
   - Update todo items

2. Employee List (/employees)
   - Displays employee data fetched from the REST API
   - Data source(example): https://restful-api.dev/

## State Management

The application uses Redux for state management:
- Redux store configuration in `store.js`
- Actions and reducers for todo operations
- Redux Thunk for handling asynchronous API calls

## API Integration

- Employee data is fetched using Axios
- API endpoint: https://restful-api.dev/
- Axios instance is configured for API calls

