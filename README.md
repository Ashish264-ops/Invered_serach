# Inverted Search

## Description
Inverted Search is a data structure-based project used to perform fast searching operations on text files. It creates an inverted index where each word stores the list of files containing that word.

This project is implemented using the C programming language and demonstrates concepts like file handling, linked lists, hashing, and searching algorithms.

---

## Features
- Create database from multiple files
- Store words with file references
- Fast word searching
- Display database contents
- Save database to file
- Update database from backup file

---

## Technologies Used
- C Programming
- Data Structures
- File Handling
- Linked List
- Hashing

---

## Project Structure
```text
.
├── main.c
├── create_db.c
├── display_db.c
├── search.c
├── save_db.c
├── update_db.c
├── hash.c
├── header.h
└── README.md
```

---

## How to Compile
```bash
gcc *.c
```

---

## How to Run
```bash
./a.out
```

---

## Example
Enter word to search:
```text
data
```

Output:
```text
Word found in:
file1.txt
file2.txt
```

---

## Concepts Used
- Inverted Index
- Hash Tables
- Linked Lists
- File Processing

---

## Author
Ashish Singh
