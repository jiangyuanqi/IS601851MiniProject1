
# Project 2 updated

## How Python uses Indentation to control Flow
Its rules are that: One or more whitespace characters (spaces or tabs) is sufficient to serve as indentation. A given indented block must use a uniform level of indentation
## Don't Repeat Yourself

Don't repeat yourself is a principle of software development aimed at reducing repetition of software patterns, replacing it with abstractions or using data normalization to avoid redundancy.
191/5000

## Design Patterns from Gang of Four
The Gang of Four are the four authors of the book, "Design Patterns: Elements of Reusable Object-Oriented Software". In this article their twenty-three design patterns are described with links to UML diagrams, source code and real-world examples for each.
## Class
Classes provide a means of bundling data and functionality together. Creating a new class creates a new type of object, allowing new instances of that type to be made. Each class instance can have attributes attached to it for maintaining its state. Class instances can also have methods (defined by its class) for modifying its state.
## Object
Python is an object oriented programming language.

Almost everything in Python is an object, with its properties and methods.
## Static
A static method is also a method which is bound to the class and not the object of the class. A static method can’t access or modify class state. It is present in a class because it makes sense for the method to be present in class.
## Property / Attribute
Everything is an object. And every object has attributes and methods or functions. Attributes are described by data variables for example like name, age, height etc. Properties are special kind of attributes which have getter, setter and delete methods like __get__, __set__ and __delete__ methods
## Method
Method is called by its name, but it is associated to an object (dependent). A method is implicitly passed the object on which it is invoked.It may or may not return any data.A method can operate on the data (instance variables) that is contained by the corresponding class
## Exception
Even if a statement or expression is syntactically correct, it may cause an error when an attempt is made to execute it. Errors detected during execution are called exceptions and are not unconditionally fatal: you will soon learn how to handle them in Python programs. 
## Unit Test
The unittest unit testing framework was originally inspired by JUnit and has a similar flavor as major unit testing frameworks in other languages. It supports test automation, sharing of setup and shutdown code for tests, aggregation of tests into collections, and independence of the tests from the reporting framework.
## Constructor
Constructors are generally used for instantiating an object.The task of constructors is to initialize(assign values) to the data members of the class when an object of class is created.In Python the __init__() method is called the constructor and is always called when an object is created.
## Factory
Factory Method is a creational design pattern used to create concrete implementations of a common interface. It separates the process of creating an object from the code that depends on the interface of the object.
## Decorator
Decorators are very powerful and useful tool in Python since it allows programmers to modify the behavior of function or class. Decorators allow us to wrap another function in order to extend the behavior of wrapped function, without permanently modifying it.
## Extend Class
Every object-oriented programming language would not be worthy to look at or use, if it weren't to support inheritance. Python not only supports inheritance but multiple inheritance as well. Generally speaking, inheritance is the mechanism of deriving new classes from existing ones. By doing this we get a hierarchy of classes. In most class-based object-oriented languages, an object created through inheritance (a "child object") acquires all, - though there are exceptions in some programming languages, - of the properties and behaviors of the parent object.
## CSV Files
A CSV is a comma-separated values file, which allows data to be saved in a tabular format. CSVs look like a garden-variety spreadsheet but with a .csv extension. CSV files can be used with most any spreadsheet program, such as Microsoft Excel or Google Spreadsheets.
## Reading Files
Reading from a CSV file is done using the reader object. The CSV file is opened as a text file with Python’s built-in open() function, which returns a file object. This is then passed to the reader, which does the heavy lifting.