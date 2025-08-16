# Taskmate - A Simple React To-Do App

Taskmate is a straightforward and easy-to-use To-Do list application built with React. It allows users to manage their tasks efficiently with features like adding, editing, deleting, and marking tasks. The application also features theme customization and persists data locally using the browser's `localStorage`.

## Features

- **Task Management:** Add, view, edit, and delete tasks.
- **Data Persistence:** Tasks are saved in the browser's `localStorage`, so they persist even after closing the browser tab or window.
- **Theme Customization:** Choose from multiple themes (light, medium, dark, and gradients) to personalize the appearance. Theme preference is also saved locally.
- **Responsive Design:** Basic responsiveness for usability on different screen sizes.
- **Clear All:** Option to quickly remove all tasks from the list.

## Tech Stack

- **Frontend:** React.js (v18+)
- **State Management:** React Hooks (`useState`, `useEffect`)
- **Styling:** CSS, CSS Variables, Bootstrap Icons
- **Persistence:** Browser `localStorage` API
- **Build Tool:** Create React App

## Setup Instructions

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository:**

    ```bash
    git clone <your-repository-url>
    cd kartikey-taskmate-react
    ```

2.  **Install NPM packages:**

    ```bash
    npm install
    ```

3.  **Run the application:**
    ```bash
    npm start
    ```
    This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

- **Adding a Task:** Type your task into the input field and click the "Add" button or press Enter.
- **Editing a Task:** Click the pencil icon next to the task you want to edit. The task text will appear in the input field. Modify the text and click the "Update" button.
- **Deleting a Task:** Click the trash bin icon next to the task you want to remove.
- **Clearing All Tasks:** Click the "Clear All" button in the task list header to remove all tasks.
- **Changing Theme:** Click on the colored circles in the header to switch between different themes.
