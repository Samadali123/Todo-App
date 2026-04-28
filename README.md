# Todo App

A clean, functional todo app built with React. Covers the full CRUD cycle — add tasks, edit them inline, mark as complete, and delete. State is managed with Context API so task data flows through the component tree without prop drilling. Toast notifications give feedback on every action. Deployed on Vercel.

Live: [my-todo-snowy.vercel.app](https://my-todo-snowy.vercel.app)


## Features

- Add new tasks with a single input
- Edit existing tasks inline
- Mark tasks as complete / incomplete
- Delete individual tasks
- Toast notifications on add, edit, and delete actions
- Persistent state within the session via Context API
- Responsive layout — works on mobile and desktop


## Project Structure

Todo-App/
├── public/               # Static assets
├── src/
│   ├── components/       # TodoItem, TodoForm, TodoList
│   ├── context/          # Context API setup — TodoContext and provider
│   ├── App.jsx           # Root component, context provider wrapper
│   └── main.jsx          # React entry point
├── index.html
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js


## Tech Stack

React · Vite · TailwindCSS · Context API · useState · useEffect · React Toastify · Vercel


## Getting Started

bash
git clone https://github.com/Samadali123/Todo-App.git
cd Todo-App
npm install
npm run dev


Opens at `http://localhost:5173`.


## Build
bash
npm run build


Output goes to `dist/`. Deploy to Vercel by connecting the repo — it auto-detects Vite.

## Topics

react` `vite` `tailwindcss` `context-api` `todo-app` `crud` `react-toastify` `frontend` `javascript` `vercel`


## Author

Syed Samad Ali — [LinkedIn](https://www.linkedin.com/in/syedsamad125)
