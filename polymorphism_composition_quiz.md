# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Literally, polymorphism means "having multiple forms"
In programming languages and type theory, polymorphism is the provision of a single interface to entities of different types or the use of a single symbol to represent multiple different types.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object. Any Java object that can pass more than one IS-A test is considered to be polymorphic.

Method overloading is an example of static polymorphism, while method overriding is an example of dynamic polymorphism

3. What can we use to implement polymorphism in Java?

When applied to object oriented programming languages like Java, it describes a language's ability to process objects of various types and classes through a single, uniform interface. Polymorphism in Java has two types: Compile time polymorphism (static binding) and Runtime polymorphism (dynamic binding).
In Java, static polymorphism is achieved through method overloading. Method overloading means there are several methods present in a class having the same name but different types/order/number of parameters.
At compile time, Java knows which method to invoke by checking the method signatures.  So, this is called compile time polymorphism or static binding.
Dynamic polymorphism in Java is achieved by method overriding.

4. How many 'forms' can an object take when using polymorphism?
Inheritance and interface implementation are two "methods" used to implement polymorphism in Java. One "class" can't exist in two forms, but more than one class can implement an interface (and more than two for that matter). We can't have different "instances" of an object, but we can have different instances (objects) of a class. 


5. Give an example of when you could use polymorphism.
Polymorphism is a method in which different instances of an object displays same behaviour.
Creating abstract and child class, implementing interface which is used by more than one class.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
We compose objects from other objects in order to get us to the functionality we need.

7. When would you use composition? Provide a simple example in Java.
The composition in the object-oriented sense refers to describing the object and seeing an object as being made up of, or composed of other objects. - car has or is made of engine, tyres, steering wheel etc.

8. What is/are the advantage(s) of using composition?
Composition allows a class to use behaviour from a group of other classes, and makes it possible for that behaviour to change at runtime.


9. When an object is destroyed, what happens to all the objects it is composed of?
 When we assign an object to be part of the composition of another object e.g. when we assign a tyre object to our car class, then we are handing ownership of tyre object over to the car object of which it is now a part.

The consequence of this is that when the car object is destroyed, all objects that it owns, or composed of, are also destroyed so the tyre object is also destroyed.
