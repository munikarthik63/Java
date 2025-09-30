## Project Overview

The Student Record System is a command-driven program designed to manage student information efficiently. It demonstrates the use of Linked Lists for dynamic data storage and allows users to perform basic operations such as adding, deleting, searching, and displaying student records.

This project is ideal for academic environments, helping students understand data structures (Linked Lists), command-based input handling, and CRUD operations in Java.

## Features

Add Student: Add new student details (Roll Number, Name, Marks).

Delete Student: Remove a student using the Roll Number.

Search Student: Find a student by Roll Number.

Display Students: Display all student records in a structured format.

Command-Driven: All operations are executed via simple commands for interactive usage.

## Commands
addstudent : Add a new student	(addstudent 3063 Karthik 92.5)

deletestudent	: Delete an existing student	(deletestudent 3063)

search : Search for a student	(search 3063)

display	: Display all student records	(display)

exit : Exit the program	(exit)

## How It Works

The program starts by asking the number of commands the user wants to execute.

Each command is read from the user input and parsed.

A switch-case structure executes the corresponding operation:

Add: Inserts a new student at the end of the linked list.

Delete: Traverses the list to find the student and removes it.

Search: Traverses the list to locate a student.

Display: Prints all student records sequentially.

The program continues until all commands are executed or the user inputs exit.

## Data Structure Used

Linked List: Provides dynamic memory allocation for student records.

# Advantages:

Efficient insertion and deletion without shifting elements.

Ideal for dynamic datasets where number of students can change frequently.

## Learning Outcomes

Understanding Linked List operations (add, delete, search, traverse).

Implementation of a command-driven program in Java.

Handling dynamic data efficiently without using built-in collection classes like ArrayList.

Developing structured and interactive mini-projects suitable for academic submissions.



