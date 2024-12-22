# Virtual Function Demo in C++

This project demonstrates the concept of virtual functions and function overriding in C++ using a simple base and derived class example.

## Description

This program illustrates how virtual functions work in C++ inheritance. It shows the difference between virtual and non-virtual function behavior when accessing derived class methods through a base class pointer.

### Key Concepts Demonstrated
- Virtual functions
- Function overriding
- Base and Derived classes
- Pointer to base class
- Runtime polymorphism

## Code Structure

The program consists of:
- A base class with two functions:
  - A virtual `print()` function
  - A non-virtual `show()` function
- A derived class that inherits from base class and overrides both functions
- A main function demonstrating the behavior using a base class pointer
