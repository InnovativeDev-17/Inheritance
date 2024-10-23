# Inheritance
Inheritance
Objective:
To understand the concept of inheritance.

Overview:
Inheritance in C++ enables a derived class to inherit properties and methods from a base class, fostering code reuse and establishing a hierarchical class structure. This mechanism supports code reusability and defines relationships between classes.

Types of Inheritance:

Single Inheritance: One derived class inherits from one base class.
Multiple Inheritance: One derived class inherits from multiple base classes.
Multilevel Inheritance: A class is derived from another derived class.
Hierarchical Inheritance: Multiple derived classes inherit from a single base class.
Algorithm: Multiple Inheritance

Define Vehicle:

Public member: company = "Ford"
Method: type() = "Mustang"
Define Specs:

Public member: mileage = "8 kmph"
Method: colour() = "Grey"
Define Car:

Inherits from both Vehicle and Specs.
Public member: seater = "4 seater"
Main:

Create an object of Car named f2.
Invoke methods from Vehicle and Specs and display the member values.
