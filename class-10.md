**JS Debugging**

* **The stack**

- JS interpreter processes **one line** of code at time.
- When a statment needs **data** from another function,it **stacks** the new function on top of the current task. 

* **EXECUTION CONTEXT & HOISTING**

* Each time a script enters a new exeution context,there're two phases of activity :

- PREPARE : (The new scope is created / Variables, functions, and arguments are created / The value of the this keyword is determined ).

- EXECUTE : (Now it can assign values to variables /Reference functions and run their code / Execute statements).

* **ERRORS**

If a JavaScript statement generates an error, then it throws an **exception**.
At that point, the interpreter **stops** and looks for **exception-handling code**.

* **Error objects :** help to find where your mistakes are,and browsers have **tools** to help you read them :

* **Syntax Error** : Syntax is not correct.

- Mismatching or unclosed quotes.
- Missing closing bracket.
- Missing comma in array.
- Malformed proerity name.

* **Reference Error**: Variable does not exist.

- Variable is undeclared.
- Named function is undefined.

* **Eval Error**

- Incorrect use of eval() function .

* **URI Error**

- Incorrect use of URI function.
- Characters are not escaped.

* **Type Error** 

- Value is unexpected data type.
- Incorrect case for **document** Object.
- Incorrect case for **write** Method.
- Method does not exist.
- DOM node does not exist.

* **Range Error**

- **Number outside of range.**

* **Error**

- Generic ERROR OBJECT.

* **NaN**

- Not a Number.

* **Logging data to the console**

* Uses of the console . log () method :

- To indicate the script is running.
- Logs the value that user entered into form field.

* **CONSOLE METHODS**

1. conso1e . info() : can be used for general information.
2. console . warn() : can be used for warnings.
3. console . error() : can be used to hold errors.

* **BREAKPOINTS**

You can pause the execution of a script on any line using **breakpoints.**

Then you can check the values stored in variables at that point in time.

* **HANDLING EXCEPTIONS**

If you know your code might fail, use **(try, catch,finally).**
Each one is given its own code block.

try {
// Try to execute this code
}catch (exception) {
// If there is an exception, run this code
}finally {
// This always gets executed
}

* **COMMON ERRORS :**

- check capitalization. **JavaScript is case sensitive**.
- Missed / Extra characters.
- Data type issues.


[Previous](class-09.md)  | [Home](README.md) | [Next](class-11.md)
