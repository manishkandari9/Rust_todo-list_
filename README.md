# Rust_todo-list_

# 📝 Rust To-Do List

Welcome to your first Rust project: a simple and powerful **To-Do List** application that helps you manage tasks efficiently! 🚀

## 📌 Features

✅ **Add Tasks**: Add new tasks with descriptions and optional due dates.  
✅ **Mark Tasks as Complete**: Toggle task status between "Pending" and "Completed".  
✅ **Remove Tasks**: Delete tasks by specifying their unique ID.  
✅ **Prioritize Tasks**: Assign priorities (**Low, Medium, High**) for better organization.  
✅ **View Tasks**: List all tasks with status, priority, and due dates.  
✅ **Persistent Storage**: Tasks are saved to a local file, ensuring data remains even after closing the program.  

---

## 🛠 Installation

### Install Rust (if not already installed)
Download and install Rust from [rust-lang.org](https://www.rust-lang.org/).

### Clone the Repository:
```sh
git clone https://github.com/yourusername/rust-todo-list.git
cd rust-todo-list
```

### Build the Project:
```sh
cargo build --release
```

### Run the Application:
```sh
cargo run
```

---

## 📌 Usage

### Add a Task:
```sh
todo add "Buy groceries" --due 2025-02-05 --priority High
```

### List Tasks:
```sh
todo list
```

### Mark a Task as Complete:
```sh
todo done 1
```

### Remove a Task:
```sh
todo remove 1
```

### View Help:
```sh
todo --help
```

---

## 📂 File Storage
All tasks are saved in `tasks.json`, allowing persistent storage between sessions.

---

## 🚀 Contributing
Want to improve this project? Feel free to fork the repository and submit a pull request! 💡


---

Happy Coding! 🎯

