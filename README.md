# Python-OOPS-Mini-Project1
# Concept: Multiple Inheritance in Python

## Question: Write a Python program to demonstrate multiple inheritance.

### 1.Employee class has 3 data members EmployeeID, Gender (String), Salary and PerformanceRating(Out of 5) of type int. It has a get() function to get these details from the user.
### 2.JoiningDetail class has a data member DateOfJoining of type Date and a function getDoJ to get the Date of joining of employees.
### 3.Information Class uses the marks from Employee class and the DateOfJoining date from the JoiningDetail class to calculate the top 3 Employees based on their Ratings and then Display, using readData, all the details on these employees in Ascending order of their Date Of Joining.

## Overview

This project demonstrates multiple inheritance in Python. It includes three classes: `Employee`, `JoiningDetail`, and `Information`. The project calculates the top 3 employees based on their performance ratings and displays their details in ascending order of their joining date.

## Classes

### Employee
- **Attributes:**
  - `EmployeeID` (String)
  - `Gender` (String)
  - `Salary` (int)
  - `PerformanceRating` (int, out of 5)
- **Method:**
  - `get()`: Retrieves employee details from the user.

### JoiningDetail
- **Attribute:**
  - `DateOfJoining` (Date)
- **Method:**
  - `getDoJ()`: Retrieves the date of joining for the employee.

### Information
- **Inheritance:** Inherits from `Employee` and `JoiningDetail`.
- **Methods:**
  - `readData()`: Calculates the top 3 employees based on their performance ratings and displays their details in ascending order of their date of joining.

## Usage

1. **Initialize the Classes:** Create instances of `Employee`, `JoiningDetail`, and `Information`.
2. **Get Employee Details:** Use the `get()` method of `Employee` and `getDoJ()` method of `JoiningDetail` to input data.
3. **Display Top Employees:** Use the `readData()` method of `Information` to calculate and display the top 3 employees.

## Requirements
**Python** <br>
**Jupyter Notebook**
