
# 📚 Library Management System (C++ Console App)

This is a simple **Library Management System** built using C++. It allows users to manage a collection of books — including adding, searching, checking out, returning, and displaying books — all through a terminal interface. Book records are saved to and loaded from a file (`library_database.txt`) to persist data between sessions.

---

## ✅ Features

- 🔍 **Search Book** by Title, Author, or ISBN
- ➕ **Add New Book** to the library
- 📥 **Checkout Book** by ISBN
- 📤 **Return Book** by ISBN
- 📃 **Display All Books** with availability status
- 💾 **Persistent Storage** using a text file

---

## 📂 File Structure

```
.
├── main.cpp               # Main source code
├── library_database.txt   # Text file for storing book data
└── README.md              # Project description
```

---

## 💻 How to Run

### 🛠 Requirements:
- C++ compiler (like g++, clang++)
- Terminal/command prompt access

### 🔄 Compile:
```bash
g++ main.cpp -o library
```

### ▶️ Run:
```bash
./library
```

> The app stores book records in a file called `library_database.txt`. If the file doesn’t exist, it will be created automatically.

---

## 📁 Book Data Format

Each book is stored in a line like:
```
<Title>,<Author>,<ISBN>,<1 or 0>
```
Where:
- `1` = Available
- `0` = Checked Out

Example:
```
The Hobbit,J.R.R. Tolkien,9780261103344,1
```

---

## 🧠 Concepts Used

- File I/O using `fstream`
- Classes and Objects
- `std::vector` for dynamic book list
- String handling with `getline` and `stringstream`
- Menu-driven programming with loops and conditionals

---

## 🧑‍💻 Author

Developed by **Abhishek**

---

## 📃 License

This project is open-source and free to use for learning and academic purposes.
