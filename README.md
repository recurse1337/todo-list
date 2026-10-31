# Todo App

A task manager built with React and TypeScript that works with a REST API. Users can add, edit, complete and delete todos, filter them by status and clear all completed tasks at once. Every change is saved on the server, and the interface shows a loader on the todos being processed and a notification if a request fails.

## Live Preview

[View the app](https://recurse1337.github.io/todo-list/)

## Technologies Used

- React 18 (functional components, hooks)
- TypeScript
- Vite
- SCSS
- Bulma
- classnames
- REST API (Fetch API)
- ESLint, Stylelint, Prettier

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/recurse1337/todo-list.git
cd todo-list
```

2. Install dependencies:

```bash
npm install
```

3. Run the project locally:

```bash
npm start
```

## Features

- Add a new todo by pressing Enter (empty titles are rejected)
- Edit a todo by double-clicking its title: Enter or blur saves, Escape cancels, an empty title deletes the todo
- Mark a single todo or all todos at once as completed
- Filter todos: All, Active, Completed
- Delete a single todo or clear all completed todos
- Counter of active todos
- Loaders on todos while requests are in progress
- Error notifications that hide automatically after 3 seconds
