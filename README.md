# to-do-list-application
#  To-Do List (Console App)

# What I Built
  I built a **simple console-based To-Do List application** in Python.  
  It allows users to **add, view, and remove tasks**, with all tasks saved in a text file so they persist between sessions.  

This project demonstrates the core logic of a task management system using Python’s built-in file handling and user input features.

---

#  Why I Built It
   I created this project to:
- Strengthen my understanding of **Python basics** such as functions, loops, conditionals, and file handling.  
- Learn how to **save and load data persistently** from a file.  
- Build a small but practical **command-line tool** that manages everyday tasks.  
- Practice **clean code structure** and **modular programming** with reusable functions.

---

#  How I Built It
The project is structured around a few core functions:

1. **`load_tasks()`** – Loads tasks from a text file (`tasks.txt`).  
   - If the file doesn’t exist, it creates an empty task list.

2. **`save_tasks()`** – Saves all current tasks to the text file so they persist after the program closes.

3. **`view_tasks()`** – Displays the list of tasks with their respective numbers.

4. **`add_task()`** – Allows the user to enter a new task, which is then added to the list and saved.

5. **`remove_task()`** – Lets the user delete a task by selecting its number.

6. **`main()`** – Controls the main program flow with a simple text-based menu:
   - View Tasks  
   - Add Task  
   - Remove Task  
   - Exit  

# Key Features
- Simple and intuitive **menu-driven interface**
- **Automatic saving** of tasks after every modification
- **Error handling** for invalid inputs and missing files
- Written in **pure Python**, no external libraries required

---

#  How to Run

        python todo.py
