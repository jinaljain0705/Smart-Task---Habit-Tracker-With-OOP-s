# 💻 Project: Smart Task & Habit Tracker

 📝 Project Definition
📌 Title: Smart Task & Habit Tracker
💡 Objective:
 To create a JavaScript-based interactive dashboard that allows users to add, edit, delete, and mark tasks/habits as complete. All updates happen in real-time on the web page using DOM manipulation, with data stored only in JavaScript memory (arrays/objects). No backend or persistent storage is used.

🧩 Project Flow
📝 Task & Habit Input
User adds tasks via a form on the web page (Title, Description, Category, Due Date, Status).
Each task is stored as an object in an array.
Tasks are dynamically rendered on the page using DOM methods like createElement, appendChild, and innerHTML.
✅ Mark Complete / Delete Task
Each task card has Complete and Delete buttons.
On click, the array is updated in memory, and the task list is re-rendered.
📊 Real-Time Dashboard
Dynamically calculate:
Total tasks
Completed tasks
Pending tasks
Overdue tasks
Update dashboard section in real-time using DOM and template literals.
🔍 Search & Filter Tasks
Search tasks by title or category using an input field.
Filter tasks by status: Completed / Pending / Overdue.
Updates happen instantly on the page without page reload.
🛠️ OOP Task Management (Class & Methods)
Task class handles task creation, editing, deletion, and marking complete.
Optional: SpecialHabit class extends Task to demonstrate inheritance.
All methods update the array and re-render the DOM dynamically.
✅ Final Dashboard Summary
Displayed on the page:
Total tasks
Completed tasks
Pending tasks
Overdue tasks
Use template literals for clear summary and real-time updates.

💡 Example Output (Rendered on Page):
Task List:

1. Morning Exercise - Pending - [Complete] [Delete]
2. Read JS Book - Completed - [Complete] [Delete]
3. Complete Assignment - Pending - [Complete] [Delete]

Dashboard:
Total Tasks: 3
Completed: 1
Pending: 2
Overdue: 0
Progress: 33%

📚 JavaScript Concepts Covered:
DOM Manipulation (querySelector, createElement, appendChild, innerHTML, addEventListener)
Arrays & Objects (store tasks in memory)
Loops (for, for…of)
Functions (task operations: add, edit, delete, complete)
Classes & OOP (Task class, inheritance, encapsulation, polymorphism)
ES6 Features (let, const, arrow functions, template literals)
Conditional Statements (task status, overdue calculation)
Responsive UI using Tailwind/Bootstrap + media queries

✅ Notes:
All data is volatile in memory; refreshing the page clears all tasks.
All interactivity is handled via DOM manipulation and JavaScript in memory.




