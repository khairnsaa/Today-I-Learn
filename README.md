# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp


## React Immutability
Immutability means that something cannot change its value or state. You can find immutable types in JavaScript itself. The String value type is a good example.

If you define a string like this:
```
var str = 'abc';
```
You cannot change a character of the string directly.

In JavaScript, strings are not arrays so you can do something like this:
```
str[2] = 'd';
```

Doing something like:
```
str = 'abd';
```
Assigns a different string to str.

So, assigning a new string generates an error (although this doesn’t relate to immutability). If you want to modify the String value, you have to use manipulation methods like replace, toUpperCase or trim. all these methods return new strings, they don’t modify the original one.
