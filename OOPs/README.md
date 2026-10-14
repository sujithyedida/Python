# Object-Oriented Programming (OOP) in Python 🐍

Welcome to the comprehensive guide on Object-Oriented Programming (OOP) in Python! This `README` covers core concepts, fundamental pillars, practical code examples, and best practices to help you write modular, reusable, and clean Python code.

---

## 📑 Table of Contents
1. [Introduction to OOP](#introduction-to-oop)
2. [The Four Pillars of OOP](#the-four-pillars-of-oop)
   - [1. Encapsulation](#1-encapsulation)
   - [2. Inheritance](#2-inheritance)
   - [3. Polymorphism](#3-polymorphism)
   - [4. Abstraction](#4-abstraction)
3. [Special (Dunder) Methods](#special-dunder-methods)
4. [Best Practices](#best-practices)

---

## 🌟 Introduction to OOP

Object-Oriented Programming is a programming paradigm that uses **classes** and **objects** to practice code reusability, organization, and modularity. 

* **Class**: A blueprint or template for creating objects.
* **Object**: An instance of a class containing specific data (attributes) and behaviors (methods).

```python
class Car:
    # Constructor method to initialize attributes
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    # Method (behavior)
    def start_engine(self):
        return f"The {self.brand} {self.model}'s engine is running. Vroom!"

# Creating an object (instantiation)
my_car = Car("Tesla", "Model 3")
print(my_car.start_engine())
