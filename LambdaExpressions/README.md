**Lambda Expressions**

Lambda expressions basically express an instance of the functional interface (interfaces with a single abstract method)
They provide a concise way to express instance of a single-method interfaces using a block of code

Functionalities of Lambda Expression
Lambda Expressions implement the only abstract function
1. Functional Interfaces: A functional interface is an interface that contains only one abstract method.
2. Code as Data: Treat functionality as a method argument.
3. Class Independence: Create functions without defining a class.
4. Pass and Execute: Pass lambda expressions as objects and execute on demand.

Structure of Lambda Expression
Syntax
Java Lambda Expression has the following syntax:
(argument list) ->(arrow token) { body of the expression }

Components:

Argument List: Parameters for the lambda expression
Arrow Token (->): Separates the parameter list and the body
Body: Logic to be executed.

Lambda Expression Parameters
There are three Lambda Expression Parameters are mentioned below:

1. Zero Parameter
2. Single Parameter
3. Multiple Parameters
1. Lambda Expression with Zero parameter 
() -> System.out.println(“Zero parameter lambda”);
2. 