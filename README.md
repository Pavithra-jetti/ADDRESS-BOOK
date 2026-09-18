# Address Book in C

## Overview

This project is a **menu-driven Address Book application developed in C**. It allows users to store and manage contact information such as name, phone number, and email address.

The project demonstrates the practical use of **structures, functions, pointers, arrays, file handling, and string manipulation** in C.

## Features

* Add a new contact
* Search for a contact
* Edit contact details
* Delete a contact
* Display all contacts
* Save contacts to a file
* Load saved contacts from a file
* Validate phone numbers and email addresses
* Prevent duplicate phone numbers and email addresses

## Technologies Used

* **Programming Language:** C
* **Compiler:** GCC
* **Platform:** Windows
* **Concepts:** Structures, Pointers, Functions, Arrays, File Handling, String Handling
* **Libraries:** `stdio.h`, `string.h`, `ctype.h`

## Project Structure

```text
Address-Book-in-C/
│
├── main.c
├── contact.c
├── contact.h
├── file.c
├── file.h
├── contacts.txt
├── README.md
└── .gitignore
```

### File Description

| File           | Description                                                                       |
| -------------- | --------------------------------------------------------------------------------- |
| `main.c`       | Program entry point and menu-driven interface                                     |
| `contact.c`    | Core contact operations such as create, search, edit, delete, list, save and load |
| `contact.h`    | Structure definitions and function declarations                                   |
| `file.c`       | File-related source file                                                          |
| `file.h`       | File-related header file                                                          |
| `contacts.txt` | File used to store contact information                                            |
| `README.md`    | Project documentation                                                             |
| `.gitignore`   | Specifies generated files that should not be uploaded to GitHub                   |

## How to Run

### 1. Clone the Repository

Open **Command Prompt** and run:

```bash
git clone <your-github-repository-link>
```

### 2. Open the Project Directory

```bash
cd Address-Book-in-C
```

### 3. Compile the Program

```bash
gcc main.c contact.c -o address_book.exe
```

### 4. Run the Program

```bash
address_book.exe
```

## Run

After running the program, a menu is displayed:

```text
1. Create Contact
2. Search Contact
3. Edit Contact
4. Delete Contact
5. List Contacts
6. Save and Exit
```

The user can select an option from the menu to manage contacts.

Contact information is stored in `contacts.txt`, allowing saved data to be loaded when the program is executed again.

## Learning Outcomes

* Gained practical knowledge of C programming
* Learned how to use structures to store contact information
* Practiced file handling for storing and retrieving data
* Improved understanding of pointers and arrays
* Learned string manipulation and input validation
* Practiced modular programming using `.c` and `.h` files
* Developed a menu-driven application using C
* Improved debugging and problem-solving skills

## Author

**Pavithra Jetti**
