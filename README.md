"# lesson2" 

## What is a scope in js ?
 - The scope is the current context of execution in which values and expressions
are "visible" or can be referenced. If a variable or expression is not in the current
scope, it will not be available for use. Scopes can also be layered in a hierarchy, 
so that child scopes have access to parent scopes, but not vice versa

- Global scope: The default scope for all code running in script mode.
-  Function scope: The scope created with a function.
 - Block scope: This scope restricts the variable that is declared 
inside a specific block, from access by the outside of the block.
- Module scope: The scope for code running in module mode.

## The 3 types of scope
![alt text](Scope.png)

# Hoisting in java script

- Hoisting is a JavaScript mechanism where variables and function 
declarations are moved to the top of their scope before code 
execution.

![alt text](i.webp)

![Alt text](image.png)


## What is TDZ js ?
- ## Temporal Dead Zone JS?
- A variable declared
with let or const
cannot be accessed
until it is declared
within its scope.

# Hoisting – Variable (var)
- There’s a temptation to think that all of the code you see in a 
JavaScript
program is interpreted line-by-line, top-down in order, as the program
execute. While that is essentially true, there’s one part of that as‐
assumption that can lead to incorrect thinking about your program.

## Hoisting – function declaration
- So, one way of thinking, sort of metaphorically, about this process, is that variable and 
function
declarations are “moved” from where they appear in the flow of the code to the top of the 
code. This gives rise to the name hoisting.


 ![Alt text](image-1.png)

 # Temporal dead zone, let and const

 ![Alt text](image-2.png)
 ![Alt text](image-3.png)