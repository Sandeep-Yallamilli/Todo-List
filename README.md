# Todo-List Web Application

1. Project Overview

Project Name: Simple Todo List

Objective: To create a clean, responsive, and user-friendly web application that allows users to manage their daily tasks effectively.

Target Audience: General users looking for a straightforward task management tool.

Core Features: Add, view, complete, and delete tasks.

2. User Interface (UI) Design & Content

A. Layout & Styling:

Overall Theme: Clean, minimalist, and modern.

Color Palette:

Background: Light grey (e.g., #f5f5f5).

Container Background: White.

Primary Color: A calming color like a soft blue or green for the "Add" button and interactive elements.

Text Color: Dark grey (e.g., #333) for primary text, lighter grey for placeholder text.

Completed Task: Light grey text with a strikethrough line.

Typography: A clean, sans-serif font (e.g., 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif).

Container: A centered card/container with a subtle shadow or border to distinguish it from the background.

B. On-Screen Components & Content:

Header:

Text: "Todo List"

Styling: Centered, large font size, subtle color.

Input Section:

Text Input Field:

Placeholder Text: "Add a new task..."

Function: A user types their task here.

"Add" Button:

Text: "Add"

Function: Clicking this adds the task from the input field to the list below.

Task List Section:

Container: A scrollable list area.

Individual Task Item:

Checkbox: A circular or square checkbox to the left of the task text.

Function: Toggling this marks the task as complete/incomplete.

Task Text: Displays the user's entered task.

Completed State: When the checkbox is checked, the text becomes grey and has a line through it (strikethrough).

Delete Button (Icon): A trash can icon (🗑️) or an "X" on the right side of each task.

Function: Clicking this removes the task from the list entirely.

4. Empty State:

Condition: When there are no tasks in the list.

Content: A simple message like "No tasks yet! Add a task above." is displayed in the task list area.

3. Functionality & User Interactions (The "Matter" of Behavior)

A. Core Features:

Adding a New Task:

User types a task into the input field.

User clicks the "Add" button or presses the Enter key.

Validation: The app should not add empty tasks.

Action:

The new task is added to the top/bottom of the list.

The input field is cleared, ready for the next task.

The new task item is displayed with an unchecked checkbox, the task text, and a delete button.

Marking a Task as Complete/Incomplete:

User clicks the checkbox next to a task.

Action:

The checkbox becomes checked.

The corresponding task text is styled with a strikethrough and a lighter color.

User clicks the checkbox again to mark it as incomplete, reverting the text style.

Deleting a Task:

User clicks the delete button (trash icon) on a specific task item.

Action: The corresponding task is immediately removed from the list and the DOM.

B. Data Persistence (Optional but common in such apps):

The list of tasks (including their completed status) is saved in the browser's localStorage.

When the page is refreshed or reopened, all tasks are loaded and displayed in their previous state (completed or not).

4. Technical Requirements

Frontend Technologies:

HTML5: For structure (input, button, list elements).

CSS3: For styling (Flexbox/Grid for layout, transitions for smooth interactions).

JavaScript (ES6+): For all interactive functionality (adding, toggling, deleting, saving to localStorage).

Deployment: The application is designed to be deployed on a platform like Vercel.


![images alt](https://github.com/sandeep-yallamilli/Todo-List/blob/b9ae557a4fb84bdd33ab7f18078f5880dfe6dc08/todo%20list.png)
