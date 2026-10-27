# Todo List App — React Context API

A simple Todo List application built with React that lets users manage daily tasks. It uses the Context API to share todo state and `localStorage` to preserve tasks across page refreshes.

## Features

- Add new tasks
- Edit existing tasks
- Mark tasks as completed
- Delete tasks
- Persist tasks in browser `localStorage`
- Manage shared state with React Context API

## Tech Stack

- React
- JavaScript (ES6+)
- React Context API and Hooks (`useState`, `useEffect`, `useContext`)
- Tailwind CSS
- Vite
- Browser `localStorage`

## Getting Started

**Prerequisite:** Node.js and npm installed.

1. Clone the repository:

   ```bash
   git clone <GITHUB_REPOSITORY_URL>
   cd <PROJECT_FOLDER>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the local URL shown in the terminal, usually `http://localhost:5173`.

## Available Scripts

- `npm run dev` — Start the development server.
- `npm run build` — Build the application for production.
- `npm run preview` — Preview the production build locally.
- `npm run lint` — Run ESLint checks.

## Project Structure

```text
src/
├── components/
│   ├── TodoForm.jsx
│   └── TodoItem.jsx
├── contexts/
│   └── TodoContext.js
├── App.jsx
├── App.css
├── index.css
└── main.jsx
```

## What I Learned

- Building reusable React components
- Sharing state and actions with the Context API
- Managing component state with React Hooks
- Implementing create, update, delete, and completion interactions
- Persisting application data with `localStorage`

