# HW_Quiz_Polymorphism_Composition

Polymorphism
1.	What does the word 'polymorphism' mean?
Polymorphism means the ability to take many forms, in the case of java, of an object to have multiple classes and interfaces.
2.	What does it mean when we apply polymorphism to OO design? Give a simple Java example.
An object can have multiple classes (their class and parent classes) and interfaces. For example, a Hybrid Engine could have an IEngine interface, and a parent class engine. The object Hybrid Engine Is an Engine, a Hybrid Engine and an IEngine.
3.	What can we use to implement polymorphism in Java?
We can use inheritance (parent classes) or interfaces.
4.	How many 'forms' can an object take when using polymorphism?
As many parent class in the inheritance chain and as many interfaces implemented on the object or its parent classes.
5.	Give an example of when you could use polymorphism.
As mentioned above you could use polymorphism to model a car engine. That way you could have a car object that includes and IEngine interface and an IEngine object as and engine property. That way you could create different cars with different engine types that implement the IEngine interface.

Composition
6.	What do we mean by 'composition' in reference to object-oriented programming?
Is when a java object is composed of other java objects. 
7.	When would you use composition? Provide a simple example in Java.
You use composition to model HAS A relationship, for example a computer has a keyboard. You could have a computer class that has a keyboard property which is keyboard object.
8.	What is/are the advantage(s) of using composition?
Easier to give single responsibility to classes and create better encapsulation, easier to change aspects of the internal classes without many side effects.
9.	When an object is destroyed, what happens to all the objects it is composed of?
The child objects also cease to exist?.
![image](https://user-images.githubusercontent.com/78230124/117997830-3fd07300-b33b-11eb-9308-567c5ac69078.png)
