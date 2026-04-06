# Student Data Management System (C)

A lightweight **Student Data Management System** built using **C language**.  
This program helps store, search, edit, and manage student information efficiently using file handling.  

---

## Features

### Admin Mode
- Add new student records  
- Edit existing data  
- Delete student records  
- Search student by Roll No.  
- View all student data  
- View statistics (sort by Roll No. or Date of Birth)

### Student Mode
- Search for your data by Roll No.  
- View all student data  
- View sorted statistics  

---

## Access Information

| Mode | Description | Password |
|------|--------------|-----------|
| **Admin** | Full access to all features | `77777789` |
| **Student** | Limited access (view/search only) | Not required |

---

## How to Run

### 1. Compile the Code
```bash
gcc student_management.c -o student_management
```

### 2. Run the Program
```bash
./student_management
```


> **Windows users:**  
> Open `student_management.c` in **Code::Blocks**, **Dev C++**, or **Turbo C**, then build and run the project.  

---

## Files

| File | Description |
|------|--------------|
| `main.c` | Source code |
| `data.txt` | Stores all student records (auto-created) |

---

## Notes

- Uses `system("cls")` for screen clearing (Windows).  
  → Replace with `system("clear")` if running on Linux/Mac.  
- Data is stored in a **binary file** named `data.txt`.  
- Uses **ANSI color codes** for colorful terminal output.  
  (Use PowerShell or Windows Terminal for proper color support.)

---


## Author

**Khush Pithva**  
🌐 [github.com/Pithva007](https://github.com/pithva007)





