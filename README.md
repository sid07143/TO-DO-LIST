# Todo App

A modern web-based Todo application built with React and Node.js, featuring full CRUD operations.

## Features

- Add new todos with title and description
- Mark todos as complete/incomplete
- Delete todos
- Clean and responsive UI
- Real-time updates

## Tech Stack

- Frontend: React.js
- Backend: Node.js with Express
- Styling: CSS3
- State Management: React Hooks
- API Calls: Axios

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository
2. Install dependencies for both frontend and backend:

```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
```

### Running the Application

1. Start the development servers:

```bash
# Start both servers (frontend and backend)
npm run dev
```

This will:
- Start the backend server on http://localhost:5000
- Start the frontend development server on http://localhost:3000

2. Open http://localhost:3000 in your browser to view the app

## Project Structure

```
todo-app/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/    # React components
│   │   └── App.js         # Main application component
│   └── public/
├── server.js              # Express backend server
└── package.json          # Project dependencies
```

## API Endpoints

- `GET /api/todos` - Get all todos
- `POST /api/todos` - Create a new todo
- `PUT /api/todos/:id` - Update a todo
- `DELETE /api/todos/:id` - Delete a todo

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
