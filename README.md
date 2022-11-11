# AirBnB clone

![AirBnB roadmap](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step1.png)

> The goal of the entire project is to deploy on our server a simple copy of the AirBnB website.

## First step: Write a command interpreter to manage our AirBnB objects

This is the first step towards building our first full web application: the AirBnB clone.
Each task is linked and will help us to:

- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of our future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

### What’s a command interpreter?

A command line interpreter is any program that allows the entering of commands and then executes those commands to the operating system. It's literally an interpreter of commands. In our case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

---

## Second step: Create a static website with HTML & CSS to display

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

- Create simple HTML static pages
- Style guide
- Fake contents
- No Javascript
- No data loaded from anything

---
File/Folder|Task
---|---
README.md | read me file
console.py | command line interpreter
models | business logic
tests | test files and packages
web_static | HTML, CSS and logo files
