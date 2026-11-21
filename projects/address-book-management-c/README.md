# Address Book Management System in C

A menu-driven console application for managing contacts, phone numbers and email addresses. The implementation is organized across multiple C source files and uses structures, dynamic memory allocation and file handling.

## Features
- Add, list, search, edit and delete contacts
- Search by name, phone number or email address
- Manage up to five phone numbers and five email addresses per contact
- Basic phone and email input validation
- Load and save contact records in a text file
- Append application messages to a log file

## Technologies
- C (C11), GCC
- Make and Makefile
- Standard C library, structures, pointers and file I/O

## Build and run
Run from this directory on Linux or Ubuntu:

```bash
make
./abk
```

Clean generated build files:

```bash
make clean
```

The program uses `telephone.csv` as its default data file. The included file is an empty starter file; do not commit personal contact information.

## Source files
- `abk_main.c` — application entry point
- `abk_menus.c` — menu and contact operations
- `abk_fileops.c` — loading, saving and memory cleanup
- `abk_log.c` — logging
- `abk.h` — shared types, constants and declarations
- `Makefile` — build rules

This is an academic console project. Please test it with sample data before using it for real contacts.
