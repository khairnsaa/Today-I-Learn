# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

today is the first day of week 4, at first all of the student join a zoom meeting and learn about creating function and object in javascript.

Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

## Function Declaration
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:
1. The name of the function.
2. A list of parameters to the function, enclosed in parentheses and separated by commas.
3. The JavaScript statements that define the function, enclosed in curly brackets,

For example, the following code defines a simple function named `multiply`:
```
function multiply(a, b) {
    const result = a * b;
    return result;

    console.log('asd');
}
```

The function square takes 2 parameter, called a and b. The function consists of one statement that says to return the parameter of the function (that is, number) multiplied by itself

Parameters are essentially passed to functions by value — so if the code within the body of a function assigns a completely new value to a parameter that was passed to the function, the change is not reflected globally or in the code which called that function.

## Function Expression
While the function declaration above is syntactically a statement, functions can also be created by a function expression.
Such a function can be anonymous; it does not have to have a name. For example, the function substract could have been defined as:
```
const subtract = function(a, b) {
    return a - b;
};
```

besides learning fundamental javascript in zoom meeting, theres also a team task for this week. for today progress, my team has created a wireframe for the project that we will create for our team assignment. we still haven't decided the name for our project. but basically we will create a simple website that can post something and write a comment in that post (just like twitter but much simpler)

here is our wireframe for this week team assignment

![image](https://user-images.githubusercontent.com/53510222/200036178-9d585ee6-2b36-45ff-a839-76caf18bad80.png)

![image](https://user-images.githubusercontent.com/53510222/200036241-da32fcb6-aba9-4c73-863e-109c6f510b0e.png)
