# React TypeScript Starter Pack
Project Description: Interactive To-Do App using React & TypeScript
This project is an interactive To-Do application built with React, TypeScript, Vite, and Sass. The application allows users to add, edit, delete, and filter tasks, while also interacting with an API.

Main Functionality:
API Integration (api.ts file)
getTodos() — fetches the user's task list.
deleteTodo(id) — deletes a task.
postTodo(title) — creates a new task.
updateTodo(todoId, data) — updates the title or status of a task.
React Components:
ErrorMessage.tsx — displays and automatically hides error messages.
TodoFilter.tsx — filters tasks (All, Active, Completed).
TodoItem.tsx — represents a single task with options to edit, delete, and toggle completion status.
Logic of TodoItem.tsx:
Double-click enables edit mode.
Pressing Enter updates the title, Escape cancels changes.
If the title is empty after editing, the task is deleted.
A loading indicator appears while updating data via API.
Technologies Used:
✅ React (state management, effects, event handling)
✅ TypeScript (component and API request type safety)
✅ Vite (fast development and build process)
✅ Sass (custom styling with modularization)

Result:
A fully functional To-Do application using React and TypeScript, integrated with an API, allowing users to add, edit, delete, and filter tasks efficiently. 🚀

-[DEMO LINK](https://valentin19939.github.io/to-do-app/)
### Available Scripts
