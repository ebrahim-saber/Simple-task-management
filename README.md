# ✅ Simple Task Management (C# Console App)

A lightweight console-based task management application built with **C#** that allows users to create, view, complete, and delete tasks. Tasks are saved to a local file (`tasks.txt`) for persistence between sessions.

---

## 🧩 Features

- Add new tasks with title and description
- View all existing tasks
- Mark tasks as completed
- Delete tasks
- Save tasks to a file and load them on app start

---

## 🖥️ Technologies Used

- C#
- .NET Core Console App
- File I/O using `StreamWriter` / `File.ReadAllLines`

---

## 📦 Project Structure
SimpleTaskManagement/
├── Program.cs # Main application logic
├── tasks.txt # Task data saved locally (auto-generated)
└── README.md # This file



---

## 🚀 How to Run

### ✅ Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (Core or 6+ recommended)

### 🏁 Steps

1. **Clone the repo**:

```bash
git clone https://github.com/ebrahim-saber/Simple-task-management.git
cd Simple-task-management

dotnet run


How It Works:
On running the app:

It tries to load previously saved tasks from tasks.txt.

Displays a menu:

1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Save and Exit

User selects an option and the appropriate action is executed.

On exit, all tasks are saved to tasks.txt.


📄 Example Output
Welcome to Task Management System 'Ibrahim Saber Gaber'
1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Save and Exit
Choose an option:

✅ Sample Task Output
1 - Task Title : Fix bugs
    Task Descriptions : Fix login bug in UI
    Task Status : Pending
-------------------------------
2 - Task Title : Meeting
    Task Descriptions : Project status meeting with team
    Task Status : Complete
-------------------------------
🧑‍💻 Author
Ebrahim Saber Gaber
GitHub: ebrahim-saber

If you want a version with badges, screenshots, or links to .NET resources, I can enhance it further. Let me know if you plan to turn this into a web or desktop version—I’ll guide you next.

