# 📝 Python To-Do List Application

A simple command-line To-Do List application built with Python. This application allows users to manage daily tasks by adding, viewing, completing, and deleting tasks. All tasks are stored in a JSON file, so they remain available even after the application is closed.

---

## 🚀 Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Delete tasks
- Save tasks permanently using a JSON file
- Simple and user-friendly command-line interface

---

## 📂 Project Structure

```
todo-app/
│── todo.py          # Main application
│── tasks.json       # Stores tasks (created automatically)
│── README.md        # Project documentation
```

---

## 🛠️ Requirements

- Python 3.7 or later

No external libraries are required because this project uses only Python's built-in modules:

- `json`
- `os`

---

## ▶️ How to Run

1. Clone the repository or download the project.

```bash
git clone https://github.com/your-username/todo-app.git
```

2. Navigate to the project folder.

```bash
cd todo-app
```

3. Run the application.

```bash
python todo.py
```

---

## 📖 Usage

When the program starts, you will see the following menu:

```
===== TO-DO APP =====
1. View Tasks
2. Add Task
3. Complete Task
4. Delete Task
5. Exit
```

Choose an option by entering the corresponding number.

### Example

```
===== TO-DO APP =====

1. View Tasks
2. Add Task
3. Complete Task
4. Delete Task
5. Exit

Choose an option: 2

Enter a new task: Complete Python project
Task added successfully!
```

---

## 💾 Data Storage

Tasks are stored in a file named `tasks.json`.

Example:

```json
[
    {
        "task": "Complete Python project",
        "completed": false
    },
    {
        "task": "Study Data Structures",
        "completed": true
    }
]
```

The file is created automatically the first time you add a task.

---

## ⚙️ Functions

| Function | Description |
|----------|-------------|
| `load_tasks()` | Loads tasks from the JSON file |
| `save_tasks(tasks)` | Saves tasks to the JSON file |
| `add_task(tasks)` | Adds a new task |
| `view_tasks(tasks)` | Displays all tasks |
| `complete_task(tasks)` | Marks a task as completed |
| `delete_task(tasks)` | Removes a task |
| `main()` | Runs the application menu |

---

## 📸 Sample Output

```
===== TO-DO APP =====

1. View Tasks
2. Add Task
3. Complete Task
4. Delete Task
5. Exit

Choose an option: 1

To-Do List

1. [✓] Finish assignment
2. [✗] Buy groceries
3. [✗] Read Python book
```

---

## 🔮 Future Improvements

- Task priorities
- Due dates
- Search tasks
- Edit existing tasks
- Categories
- Colored terminal output
- GUI version using Tkinter or PyQt
- Database support (SQLite/MySQL)
- User authentication

---

## 📚 Technologies Used

- Python
- JSON
- OS Module

---

## 👨‍💻 Author

Developed as a beginner-friendly Python project to demonstrate:

- File handling
- JSON data storage
- Functions
- Exception handling
- Lists and dictionaries
- Command-line application development

---

## 📄 License

This project is open source and available under the MIT License.
