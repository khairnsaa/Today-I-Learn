# Today-I-Learn Day 5

Today i learn in LearningX - Sparta Coding Club Bootcamp

### Starting assignment

By definition, a Dynamic programming language is a high-level programming language that at runtime executes many common programming behaviors that static programming languages perform during compilation and these behaviors could be adding a new code, modifying the type system, or extending objects. A language is called Dynamically typed if the ‘type’ of a variable is checked only during the runtime unlike at compile time in a statically typed language. With this support, the developers need not specify the data type of any variable while writing the code.

Some of the JavaScript features which make it dynamic are: JavaScript is a dynamic programming language & javascript is a loosely type languange

#### why javascript is loosely typed languange?

if you're using javascript you don’t have to specify what type of information will be stored in a variable in advance. also when you want to create a variable containing string data type, there's no restriction for you to use double quotes, you can use single quotes or double qoutes. Many other languages, like Java, require you to declare a variable’s type, such as int, float, boolean, or String. But, in javascript if you want to declare a variable you just need to use var (old version), let and const.

Typecasting in JavaScript means converting one data type to another data type i.e., the conversion of a string data type to Boolean or the conversion of an integer data type to string data type. The typecasting in JavaScript is also known as type conversion or type coercion.

there are 2 types of type casting in javascript, implicit and explicit.

The implicit type casting is the conversion of data type done due to the internal requirement or automatic conversion by the compiler or the interpreter.
for example, JavaScript expects a boolean value in a conditional expression. So JavaScript will temporarily convert the value in parentheses to a boolean to evaluate the if expression

The second type casting the explicit type casting is done forcefully by the developer for the sake of a good line of code. In JavaScript the type casting can be done only for strings, numbers and Boolean (object) data types.
for example, The parseInt() function converts its first argument to a string, parses that string, then returns an integer or NaN.

when you want to compare 2 variables in programming language usually you'll si this operator (==) but in javascript there's also this operator (===). both is comparison operator, the different is if you using (==) you only checks the equality of two operands without considering their type, but if you're useing (===) you not only check the equality, but also the data type of both variables.

#### undefined vs null
There are several differences between null and undefined, which are sometimes understood as the same.
Null: It is the intentional absence of the value. It is one of the primitive values of JavaScript.
Undefined: It means the value does not exist in the compiler. It is the global object.


### Primitive type data and Reference type data.
Whenever you create a variable in JavaScript, that variable can store one of two types of data, a primitive value or a reference value. If the value is a number, string, boolean, undefined, null, or symbol, it's a primitive value. If it's anything else (i.e. typeof object), it's a reference value.

### shallow copy vs deep copy
deep copy: A deep copying means that value of the new variable is disconnected from the original variable while a shallow copy means that some values are still connected to the original variable.

shallow copy: When a reference variable is copied into a new reference variable using the assignment operator, a shallow copy of the referenced object is created. In simple words, a reference variable mainly stores the address of the object it refers to. When a new reference variable is assigned the value of the old reference variable, the address stored in the old reference variable is copied into the new one. This means both the old and new reference variable point to the same object in memory. As a result if the state of the object changes through any of the reference variables it is reflected for both.

### How to make Immutable Object?
If you wish for an object to not be able to be modified you can use Object.freeze(). 
Object.freeze() method freezes an object: that is, prevents new properties from being added to it; prevents existing properties from being removed; and prevents existing properties, or their enumerability, configurability, or writability, from being changed.
