# SE Assignment

## Author

**Sanchit Kumar Dogra**  
**IMT2022035**

# Design Decisions

## 1. Separation of HTML, CSS, and JavaScript

**Reasoning**: This is a best practice in web development for ease of maintenance.

- **HTML** is responsible for the structure of the page.
- **CSS** is responsible for the styling.
- **JavaScript** manages interactivity (adding tasks, marking them as completed, deleting, etc.).

## 2. Creating Dynamic List Items with Task Features

**Reasoning**: Each task is dynamically created, and key task features are added:

- **Checkbox** to mark tasks as completed.
- **Edit button** to modify the task description.
- **Delete button** to remove the task from the list.

## 3. Edit and Delete Functionality

**Reasoning**: The Edit button uses `prompt()` to allow users to modify the task, and the Delete button removes tasks.

## 4. Dynamic Event Listeners

**Reasoning**: Event listeners are attached to each task’s edit, delete, and checkbox elements when the task is created. This ensures that each task is interactive immediately after being added.
