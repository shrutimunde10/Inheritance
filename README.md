TITLE: Inheritance in C++

AIM: To implement inheritance in programs using C++

THEORY: In C++, inheritance is a core principle of object-oriented programming where a new class, known as the derived class, can inherit properties and behaviors from an existing class, 
referred to as the base class. Inheritance promotes code reusability, as the derived class can access and extend the functionality of the base class. 
It enables the creation of class hierarchies, allowing for more specialized classes to be derived from more general ones. 
C++ supports public, protected, and private inheritance modes, governing the visibility of inherited members. Inheritance is a fundamental concept for achieving polymorphism, 
encapsulation, and code organization in C++ programs.

ALGORITHM: 1.Start
2.Declare a class vehicle with two public member variables: brand set to "BMW" and color set to "White."
3.Declare a class Features that inherits from the vehicle class.
4.In the Features class, declare two additional public member variables: engine set to "BMW N52" and mileage set to "17.42 Kmpl."
5.In the main function:
      a.Create an instance of the Features class named car.
      b.Display the value of the color member variable of the car object.
      c.Display the brand and engine member variables of the car object with a space in between.
6.End the program.

CONCLUSION: In C++, inheritance is a powerful object-oriented programming concept that facilitates code reuse and hierarchy creation.
It allows derived classes to inherit properties and behaviors from base classes, enhancing code organization and maintainability. 
By supporting public, protected, and private inheritance modes, C++ offers fine-grained control over the visibility of inherited members.
Inheritance is essential for achieving polymorphism and encapsulation, enabling the development of complex, modular, and extensible software systems.
