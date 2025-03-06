# KanbanBoardApplication

This Kanban board application allows users to manage tasks across different stages: To Do, In Progress, Peer Review, and Done. The board supports drag-and-drop functionality for task movement and includes a search box to filter tasks by title.

## Features

- **Kanban Board Layout**: Four sections/columns representing task stages:

  - To Do
  - In Progress
  - Peer Review
  - Done

- **Task Cards**: Each task card displays:

  - Task Title
  - Task Description
  - Tasks are draggable between columns.

- **Drag and Drop Functionality**: Move tasks between columns and place them in the correct position.
- **Search Functionality**: Filter tasks in all columns based on the search input.
- **Add New Tasks**: Create new tasks in the To Do column.
- **Responsive Design**: The UI is fully responsive.
- **State Management**: Uses Redux for state management.
- **Styling**: Uses Material-UI for styling.

## Technologies Used

- ReactJS
- Redux
- React-DnD (for drag-and-drop functionality)
- Material-UI (for styling)
- Local Storage (for data persistence)

## Getting Started

### Prerequisites

- npm

### Installation

Usage

Creating a New Task
Click the floating button to open the new task modal.
Fill in the task title and description.
Click "Create" to add the task to the "To Do" column.
Moving Tasks
Drag a task card to move it to a different column.
Drop the task card in the desired column.
Searching Tasks
Type in the search bar to filter tasks by title.
Matching tasks will be displayed, and non-matching tasks will be hidden.

Features

1. Kanban Board Layout

Four Sections/Columns:
To Do: Tasks that need to be started.
In Progress: Tasks that are currently being worked on.
Peer Review: Tasks that are completed and are awaiting review.
Done: Tasks that are completed and reviewed.
Each section displays the tasks relevant to that stage.

2. Task Cards
   Task Information:
   Task Title: Displayed prominently on the card.
   Task Description: Displayed in a shortened form to fit within the card.
   Draggable: Tasks can be dragged and dropped between columns.

3. Drag and Drop Functionality
   Drag-and-Drop: Implemented using React-DnD library.
   Movement: Tasks can be moved from one column to another.
   Positioning: Tasks can be placed in a specific order within a column.

4. Search Functionality
   Search Bar: Located at the top of the board.
   Filtering: Filters tasks based on the search input in real-time.
   Matching Tasks: Only tasks that match the search query are displayed.
   Non-Matching Tasks: Tasks that do not match the search query are hidden.

5. Add New Tasks
   Floating Button: A button that opens a modal to create new tasks.
   Task Creation Form:
   Task Title: Input field for the task title.
   Task Description: Input field for the task description.
   New Tasks: Created tasks are added to the "To Do" column.

6. Responsive Design
   Responsive UI: The application layout adjusts to different screen sizes, ensuring usability on both desktop and mobile devices.

7. State Management
   Redux: State management is handled using Redux.
   Actions and Reducers: Organized actions and reducers to manage the state of tasks.

8. Styling
   Material-UI: Used for consistent and modern styling of the application components.
   Custom Styles: Additional styles for specific components to ensure a polished look.

9. Data Persistence
   Local Storage: Tasks are stored in local storage, ensuring that task data persists across page reloads.
