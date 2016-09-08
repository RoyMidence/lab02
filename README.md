# Lab 02 -- Chapter 01

## Define the following terms:
object: An instance of a Class
class: the basis or blueprint for an object
instance: specific realization of an object
method: collection of statements used to manipulate or access information from an object of that class.
signature: method name and number and type of parameters
parameter: an input request from the parameter
type: integers and Strings and doubles and stuff
state: The textbook says "the set of values of all attributes defining an object"
source code: Collection of commands that compiles and creates an executable program.
return value: the value being returned by a method
compiler: part of program that translates source code into machine code

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?
0 - int
"hello" - String
101- int
-1- int
true- boolean
"33"- String
3.1415- double

## What would you have to do to add a new field, for example one called name, to a circle object?

create it before the constructor and add a private access modifier. ex *private String name*;

## Write the header for a method named send that has one parameter of type String, and does not return a value.

public void send(String msg)

## Write the header for a method named average that has two parameters, both of type int, and returns an int value.

public int average(int num1, int num2)

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.

It is an object of class Book.

## Can an object have several different classes? Discuss.

I supposed if you count all super classes or if it is using any classes as its
variables then yes. But if you don't then no.
