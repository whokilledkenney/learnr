# 1. Introduction

* R language is a dialect of S. 
* R is command driven, and the default prompt used to enter commands is `>`. Each command is executed one at a time.  

# 2. Objects 

* In every computer programming language, variables provide a way of accessing the data stored in the computer's memory. 
* R doesn't provide direct access to that data stored in the computer's memory, but rather provides a variety of specialized data structures, called **_objects_**. 
* Objects are referred to through symbols or variables. In R, symbols themselves are objects and can be manipulated. This is what differentiates R from other languages. 
* R objects can be basically anything. 
* We can do _operations_ on objects. This means that objects are communicating messages to other R objects, and the operations are how the object responds to that message. 
* R objects are _immutable_, which means that you don't have to write code in order to change an object's state. Instead, you work with objects as values, and operations on objects create new objects when you need a new "state". 
* Think of R objects and classes as abstract data structures.

### 2.1 Types of Objects

* You have values (objects) and associated operations you can do on these values. These processes are usually implemented via **_classes_** or a _class system/hierarchy_ in most object-oriented languages.  
* _Type specifications_ define which _functions_ can be applied to certain objects.
* **_Types_** determine what you can do with objects.
* The operations you can do with a particular object are simply determined by which functions you can call on the objects.
* You can think of an object's type as its data structure.
