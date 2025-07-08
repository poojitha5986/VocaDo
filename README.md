# ZenDo 🧘‍♀️✅  
*Calm and productive task handling — a mindful blend of “Zen” and “To-Do” to help you stay organized, stress-free, and on track.*

---

## 🔥 Project Overview

**ZenDo** is a feature-rich To-Do List Application built entirely from scratch using **HTML, CSS, and JavaScript**. The project focuses on creating a user-friendly task manager that supports **task creation, editing, deletion, priority tagging, dark/light mode**, and even **voice command interactions**.

---

## 🚀 Features

- 🎙️ **Voice command** support for adding, editing, and deleting tasks  
- ➕ Add, ✏️ Edit, ✅ Complete, and 🗑️ Delete tasks  
- 📅 Due date selection with calendar picker  
- 🔴🟡🟢 Task priority categorization  
- 🔍 Search bar to filter tasks in real-time  
- 🌓 Toggle between light and dark themes  
- 🧠 Persistent storage using `localStorage`  
- 📊 Sort tasks by due date or priority  
- 🚫 Prevents duplicate task entries  
- 🎬 Preloader animation and typing effect on title  

---

## 🛠️ Tech Stack

| Technology     | Purpose                              |
|----------------|---------------------------------------|
| HTML           | Structure of the application          |
| CSS            | Styling the UI                        |
| JavaScript     | Logic and interactivity               |
| Flatpickr      | Date picker for due dates             |
| Web Speech API | For handling voice commands           |
| localStorage   | To persist tasks across sessions      |

---

## 🧩 How I Built It (Development Workflow)

Here’s a step-by-step breakdown of how I developed **ZenDo**:

1. **Created `index.html`**  
   - Structured the layout with task input, buttons, filters, and sections.  
   - Added voice command start button, search bar, and task list container.  
   - Linked to `style.css`, `flatpickr`, and `index.js`.

2. **Designed `style.css`**  
   - Used Flexbox and modern color schemes.  
   - Styled dark and light mode themes.  
   - Visually differentiated tasks by status and priority.

3. **Developed `index.js`**  
   - Handled user interactions (add, edit, delete).  
   - Added validations for duplicates.  
   - Enabled sorting by date and priority.  
   - Integrated `flatpickr` for selecting due dates.

4. **Voice Command Feature**  
   - Utilized Web Speech API to accept spoken task commands.  
   - Parsed input and performed task actions.  
   - Example voice prompts:  
     - `"Add assignment due date 16th Nov priority High"`  
     - `"Edit task assignment to research"`  
     - `"Delete task assignment"`

5. **localStorage Integration**  
   - Stored tasks as JSON strings.  
   - Reloaded and displayed them after refresh.  
   - Stored theme preference.

6. **Dark Mode Toggle**  
   - Toggle switch to switch between light and dark UI.  
   - Theme preference saved in localStorage.

7. **UX Enhancements**  
   - Typing animation on title.  
   - Preloader during app load.  
   - Alert boxes for success and error messages.

---

## 🧪 How to Run This Project Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/poojitha5986/ZenDo.git
