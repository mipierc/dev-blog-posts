## Dev Post 3

##### Author: Michael Pierce

###### Date: 17 February 2022

#### __Test-Driven Development__

Testing is the most important part of the development process. In my programming experience, I don't believe I have run a single program and had it function as intended on the first attempt. Test-driven Development or TDD for short is a software development process reliant on converting requirements into test cases prior to the implementation. It essentially switches the traditional order, where you would develop the software first and then test it. TDD works best with modular, flexible, and extensible code. This is partially because this methodology requires developers to focus on smaller units that can be written and tested and brought together later. It inspires smaller and more focused classes and looser coupling. Inversely, it doesn't function well when full functional tests are required to determine success or failure because of the extensive use of unit tests. Some examples would be user interfaces and programs that interact with databases. The developer who writes the test is also writing the code. This can cause things to get missed, as the test may share the same blind spots as the code.

#### __OOP vs. Functional__

OOP, or Object-oriented programming, is a computer programming model that organizes software design around objects rather than functions and logic. OOP focuses on the objects developers want to manipulate rather than the logic required to manipulate them. OOP has become increasingly popular and is best suited for large, complex, and active software projects. The organization of an object-oriented program also makes the method beneficial to collaborative development, where projects are divided into groups. Additional benefits of OOP include code reusability, scalability, and efficiency. The structure of OOP include the following:

+ __Classes__ are user-defined data types that act as the blueprint for individual objects, attributes, and methods.
+ __Objects__ are instances of a class created with specifically defined data. Objects can correspond to real-world objects or an abstract entities. When class is defined initially, the description is the only object that is defined.
+ __Methods__ are functions that are defined inside a class that describe the behaviors of an object. Each method contained in class definitions starts with a reference to an instance object. Additionally, the subroutines contained in an object are called instance methods. Programmers use methods for reusability or keeping functionality encapsulated inside one object at a time.
+ __Attributes__ are defined in the class template and represent the state of an object. Objects will have data stored in the attributes field. Class attributes belong to the class itself.

Functional programming is the opposite of OOP, instead of focusing on objects, it focuses on binding everything in pure mathematical functions. It focuses on "what to solve". It uses expressions instead of statements. The structure of functional programming include the following:

+ __Pure functions__ have two main properties. First, they always produce the same output for the same arguments irrespective of anything else.
Secondly, they have no side effects i.e. they do not modify any arguments or local/global variables or input/output streams.
Later property is called immutability. The pure function’s only result is the value it returns. They are deterministic.
+  __Recursion__ There are no “for” or “while” loops in functional languages. Iteration in functional languages is implemented through recursion. Recursive functions repeatedly call themselves, until it reaches the base case. 
+ __Variables are Immutable__ In functional programming, we can’t modify a variable after it’s been initialized. We can create new variables – but we can’t modify existing variables, and this really helps to maintain the state throughout the runtime of a program.