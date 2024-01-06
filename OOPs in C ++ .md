                Classes

A class is an expanded concept of a data structure: instead of holding only data, it can hold both data and 
functions. 

An object is an part of a class. In terms of variables, a class would be the type, and an object would be the 
variable. 

            Acess Specifier 

An access specifier is one of the following three

keywords: private, public or protected. These specifiers modify the access rights that the members following 
them acquire: 

* private members of a class are accessible only from within other members of the same class or from 
their friends. 

*  protected members are accessible from members of their same class and from their friends, but also 
from members of their derived classes. 

*  Finally, public members are accessible from anywhere where the object is visible. 

            Friend Function

1. What is a friend function?

Friend function is a non-member function that can access the private and protected members of a class, 
even though it doesn't belong to that class itself.It's declared using the friend keyword within the class definition.

2. Why use friend functions?

* Overcoming encapsulation: In specific cases, you might need to allow external functions to access private class data for:
Overloading operators

* Implementing tightly coupled classes

* Providing helper functions for complex operations

