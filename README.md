# JAVA-Notes

## Java Cheat Sheet
# 1. Java Data Types
# Java has 8 primitive data types that help store specific types of data in memory efficiently.

# Data Type	Size (bits)	Description	Example
byte	8	Stores whole numbers from -128 to 127. Useful for saving memory in large arrays.	byte b = 10;

```
 short	16	Stores whole numbers from -32,768 to 32,767.	short s = 500;

int	32	Stores whole numbers from -2,147,483,648 to 2,147,483,647. Default for integers.	int i = 1000;

long	64	Stores whole numbers, large range from -2^63 to 2^63-1. Use L suffix to declare.	long l = 1000L;

float	32	Stores fractional numbers, sufficient for 6-7 decimal digits. Use f suffix to declare.	float f = 5.75f;

double	64	Stores fractional numbers, sufficient for 15 decimal digits. Default for decimals.	double d = 19.99;

char	16	Stores a single 16-bit character/letter or ASCII value.	char c = 'A';

boolean	1	Stores true or false values, used in conditional statements.	boolean flag = true;

 ```


# 2. Object-Oriented Programming (OOP) Concepts
Object-Oriented Programming (OOP) is a programming paradigm that structures code around objects rather than actions. It enables developers to represent real-world entities through classes and objects and promotes modular, organized, and reusable code. Java’s OOP principles include Encapsulation, Inheritance, Polymorphism, and Abstraction.

# Key OOP Principles
# Encapsulation

Definition: Encapsulation involves bundling data (attributes) and methods within a class while restricting direct access from outside.
Purpose: Protects data by only allowing access through controlled methods (getters/setters).
Example: Using private fields with public getter and setter methods.

# Inheritance

Definition: Inheritance allows one class (child) to acquire the properties and methods of another class (parent), forming a hierarchy.
Purpose: Promotes code reuse and allows for extending existing code without modification.
Example: Dog class inheriting Animal class properties.

# Polymorphism

Definition: Polymorphism allows objects to be treated as instances of their parent class while enabling them to call overridden methods specific to their actual class.
Purpose: Enables flexibility and efficient code reuse with a common interface for different implementations.
Example: A sound() method could be implemented differently for Dog and Cat subclasses.

# Abstraction

Definition: Abstraction hides complex implementation details and exposes only essential features to interact with an object.
Purpose: Simplifies code by allowing interaction through simplified interfaces, focusing on what the object does rather than how.
Example: An abstract Shape class with a draw() method that is implemented by subclasses like Circle and Rectangle.
