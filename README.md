# Student Record System

A simple command-line student record management system written in Python. It allows you to add, search, update, delete, import, and list student records stored in a CSV file.

---

## Features

- Add new students
- Search students by Registration Number or Name
- Update existing student details
- Delete student records
- Import multiple student records from a CSV file
- List all student records

---

## Requirements

- Python 3.x

*(No external libraries required, only the built-in `csv` and `os` modules)*

---

## Usage

1. Clone this repository or download the script file (`student_system.py`).

2. Run the script:


3. Follow the on-screen menu to perform various operations.

---

## How it works

The system stores student information in a file named `students.csv`. If the file doesn't exist, it creates one with headers. You can perform CRUD operations (Create, Read, Update, Delete), import data from other CSV files, and view all records.

---

## Files

- `student_system.py` — Main script implementing the student record management system.

---

## Notes

- Ensure CSV files used for importing have the correct format with headers: `name,Reg_no,Class,Age`.
- Student Registration Numbers should be unique.

---

## Contributing

Feel free to fork, modify, and improve this project. Pull requests are welcome!

---

## License

This project is for educational purposes. Use at your own discretion.


