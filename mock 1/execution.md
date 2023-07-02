Execution context in JavaScript is the environment in which code is executed. It includes variables, functions, and other data structures that determine how the code is executed and how it interacts with its surroundings. Each time a function is invoked, a new execution context is created.

To understand execution context better, let's break it down into three components: the Variable Environment, the Scope Chain, and the "this" keyword.

Variable Environment:
The Variable Environment contains variables and functions defined within the current scope. It consists of two main parts:

Variable Object (VO): It stores function declarations, function arguments, and variable declarations. During the creation phase of an execution context, the Variable Object is set up with these declarations.

Lexical Environment: It represents the current scope and includes the Variable Object along with any parent scopes.