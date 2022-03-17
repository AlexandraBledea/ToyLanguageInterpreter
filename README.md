# ToyLanguageInterpreter
### A custom "toy" language interpreter built on Java

-----

# Used Concepts
- Layered architecture
- JavaFX for GUI
- Encapsulation, interfaces, streams
- MVC pattern

---

# Instructions:
- variable declaration & assignment
- if
- while
- fork (multi-threading)
- file opening, closing and reading
- printing
- heap allocation, reading and writing
- logical expressions
- arithmetical expressions
- relational expressions

---

# Variables Types:
- Bool
- Int
- String
- Reference

---

# Functionalities
- Storing instructions in execution stacks
- Storing local variables in symbol tables
- Storing BufferedReader objects into a file table for file operations
- Shared heap across all the states created by a program - allocation, reading, writing, garbage collector
- Storing printing output in an output table
- Upon forking, a new program state with a unique ID is being created
- Program states: each state has an ID, a symbol table and an execution stack

---

# Demo
- Examples Window:
- ![ExamplesWindow](https://user-images.githubusercontent.com/72063091/158892930-398047e7-099e-49a7-83f3-03952b6a4264.png)
- ![ExecutionWindow](https://user-images.githubusercontent.com/72063091/158892998-4d77c73c-a1a6-4e06-ba2d-e68f5a72fb2b.png)
