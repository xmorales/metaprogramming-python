# Metaprogramming with Python
- A small course to explain metaprogramming in Python. 
- This has been prepared for a 1,5h workshop and shared for everyone interested.

Explained in Markdown to allow a conversion to mindmap using [Markmap](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode).
Each chapter will have code snippets under "workshop" folder to explain with examples.

## Tools needed
- Python 3.10
- Jupyter Notebook (pip3 install notebook)
- (optional) MarkDown with VSCode+Markmap

## Summary
- Introduction
  - What is a Class
  - Meta vs Hierarchy
  - type function
- Decorators
  - The making of
  - Real world examples
- Metaclasses
  - Do you need them?
  - Real world examples

## Introduction
- Meta == Greek word for "beyond"
- Metadata == data about data
- Metaprogramming == programs that manipulate programs

### What is an object in Python?
- string
- A function
- A class definition
- An instance of a class
- Everything

### What is a Class in Python?
- Object that creates a new object, or instance
- Contains functions and attributes
- Can create an instance
- Who creates a class?
  - See the workshop

### Hierarchy of classes
- A class can inherit another
  - Can use all attributes and functions of the base/super class
  - In python any Class is always a derived class, at least of the superclass 'object'
    - See the workshop
- Multiple inheritance is possible
  - the search for attributes inherited from a parent class goes depth-first, left-to-right, not searching twice

### Workshop
- How classes and instances are created
- How inheritance work
- What is type

## Decorators
- Let's do a trip
- From the concept
- Through decorator construction
- Until real examples

### Workshop
- The making of a decorator
- Real world examples

## Metaclasses
- Do we need them?
- Real world examples
## References
- https://docs.python.org/3/tutorial/classes.html
- https://realpython.com/primer-on-python-decorators/
- https://realpython.com/python-metaclasses/
- https://developer.ibm.com/tutorials/ba-metaprogramming-python/
