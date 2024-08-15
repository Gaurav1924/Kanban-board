Welcome to the Kanban Board Application! This project provides a versatile Kanban board for managing tasks and notes. It features a clean interface and various interactive elements to enhance task management.

Features
**Task Management:** Create new tasks with a modal that includes color selection and description input.

**Edit Task:** Toggle between editing and viewing modes with a lock/unlock icon on each task card.

**Remove Task:** Activate removal mode to delete tasks by clicking on them.

**Filter by Color:** Click color icons to filter tasks based on their assigned color.

Dynamic Interaction:
Add tasks via the Add button.
Edit task descriptions using the lock/unlock icon.
Remove tasks by activating the remove button and clicking on tasks.
Filter tasks by color using the top color icons.

Design Decisions
**Color Coding:** Tasks are color-coded with a top strip to facilitate visual categorization and filtering.
**Editable Tasks:** The lock/unlock feature allows for switching between editable and viewable states.
**Removal Mode:** The +/- button toggles the removal mode to avoid accidental deletions.

Challenges and Solutions
**Managing State Across Components:** Used global variables and JavaScript functions to manage and synchronize states (e.g., editing, removal) across various components.
**Event Handling:** Implemented event listeners for handling user interactions such as clicks and key presses, ensuring correct responses and state management.
**Dynamic Task Management:** Employed JavaScript for real-time DOM manipulation to add, update, and remove task cards efficiently.
