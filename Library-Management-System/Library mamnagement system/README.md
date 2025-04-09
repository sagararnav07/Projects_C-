Here’s a `README.md` file for your Bank Data Management System (which seems to actually manage a **Library Management System** based on the code). You can rename it if needed, but I'll keep the original naming for now:

---

```markdown
# Library Management System

## 📚 Overview

This is a simple **Library Management System** built in C++ that enables basic operations such as:

- 📖 Viewing all books
- 🔍 Extracting details of a specific book by its ID
- ➕ Adding new books (Admin access)

All book records are stored in a local file named `bookData.txt`. Each entry contains:
- Book ID
- Book Name
- Author Name

## ⚙️ Features

### 1. Show All Books
Displays a list of all books in a formatted manner, showing the **Book ID**, **Book Name**, and **Author Name**.

### 2. Extract Book by ID
Lets the user search for a specific book by entering its ID and displays its details if found.

### 3. Add New Book (Admin)
Allows an admin to input a new book entry. The details are appended to the `bookData.txt` file.

### 4. Exit
Exits the program.

## 🛠️ How it Works

The program uses basic file handling through C++'s `fstream`. Book entries are stored in the format:
```
ID*Book Name*Author Name
```

- `*` is used as a delimiter for parsing book information.
- File operations ensure persistent data storage between program executions.

## 💡 Example

```
----------------------------------
1-Show All Books
2-Extract Book
3-Add books(ADMIN)
4-Exit
----------------------------------
Enter Your Choice :: 1
```

## 🧑‍💻 Author

**Arnav Sagar**

## 📁 Files

- `LibraryManagementSystem.cpp`: Main source code
- `bookData.txt`: Data storage file (created on runtime)

## 🚀 Getting Started

1. Compile the code:
```bash
g++ LibraryManagementSystem.cpp -o library
```

2. Run the program:
```bash
./library
```
