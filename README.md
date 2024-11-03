# Linked List String Operations Project

This project implements a linked list that stores strings, allowing various operations on the list. Developed for a **System Programming course**, this project demonstrates the use of dynamic memory allocation and string manipulation in C.

---

## 📋 Project Overview

The project is designed to handle a list of strings, with each node holding a single string. You can think of it as a list that can store and manipulate sentences or even stories by allowing additions, deletions, sorting, and various queries.

### Key Features

1. **Insert Strings**:
   - Add words to the list either in sequence or at a specific index.
2. **Display Operations**:
   - Print the entire list.
   - Display the length of the list.
   - Show the string at a specified index.
3. **Search and Count**:
   - Count occurrences of a specific string.
4. **Delete Operations**:
   - Remove all occurrences of a specific string.
   - Delete the node at a specified index.
   - Clear the entire list.
5. **Sorting**:
   - Sort the list lexicographically.
   - Check if the list is already sorted lexicographically.
6. **Additional Functionality**:
   - Reverse the list.

### Supported Commands
The main program (`Main.c`) provides a menu with the following commands:

- `A` - Insert multiple words into the list, separated by spaces.
- `B` - Insert a string at a specified index.
- `3` - Print the entire list.
- `4` - Print the length of the list.
- `5` - Print the string at a specified index.
- `6` - Count the number of times a character appears in the list.
- `7` - Count occurrences of a specific string.
- `8` - Delete all occurrences of a specific string.
- `9` - Delete the node at a specified index.
- `10` - Reverse the list.
- `11` - Clear the entire list.
- `12` - Sort the list lexicographically.
- `13` - Check if the list is sorted lexicographically.
- `0` - Exit the program.

---

## 🗂 Project Structure

- `Makefile` - Compilation instructions for the project.
- `StrList.h` - Header file containing the function declarations for linked list operations.
- `StrList.c` - Implementation of linked list operations for managing and manipulating strings.
- `Main.c` - Main program that provides a user interface to execute list operations.

---

## 🛠 Compilation and Execution

### Requirements
- **Operating System**: Ubuntu Linux
- **Compiler**: GCC with warning flags enabled for error-free compilation

### Compilation
To compile the project, navigate to the project directory and run:
```bash
make
