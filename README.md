# Class
Practice exercises covering Object-Oriented Programming (OOP) concepts, classes, and inheritance in Python.


#  Python Object-Oriented Programming (OOP) Exercises

This repository contains practical exercises designed to master the core principles of Object-Oriented Programming (OOP) in Python. The project focuses on class creation, object instantiation, inheritance, and method overriding.

###  Concepts Covered
* **Class & Instance Attributes:** Defining attributes using the `__init__` constructor.
* **Inheritance:** Creating child classes (`Car`, `Train`) that inherit attributes and methods from a parent class (`Vehicle`).
* **Method Overriding:** Customizing behavior in child classes by overriding the parent class methods (e.g., `fare()`).
* **`super()` Function:** Utilizing the parent class's logic and extending it within the child class.

###  Implementation Details
The codebase includes a class hierarchy:
* `Vehicle` (Attributes: `maxspeed`, `color`, `seating_capacity`)
  * `Car` (Inherits all properties from Vehicle)
  * `Train` (Overrides the fare method to include an extra 10% maintenance charge)
