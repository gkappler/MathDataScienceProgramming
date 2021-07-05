---
title: Curriculum Course MDSP - Week 5
---

[course overview](../)

## Homework

(materials below)

1. What is a variable in julia? What is the type of a variable in julia?
A variable, in Julia, is a name associated (or bound) to a value. It's useful when you want to store a value (that you obtained after some math, for example) for later use.
Static type systems, where every program expression must have a type computable before the execution of the program. 
Dynamic type systems, where nothing is known about types until run time, when the actual values manipulated by the program are available. 

2. What is a function in julia?    
A function in Julia is an object that takes a tuple of arguments and maps it to a return value. A function can be purely mathematical or can modify the state of another object of the program.
With Julia's function, we can write larger calculations but in very fewer lines of code, because the functions support full notations.
Functions in Julia can be of multiple types as per the requirement. Some of these types are listed below:
A function with single expression
A function with multiple expressions
A function with no argument
A function with variable arguments, etc.

3. Compare what "function" means in julia with what "function" means in mathematics
A function in Julia is an object that takes a tuple of arguments and maps it to a return value. However, function, in mathematics,is an expression, rule, or law that defines a relationship between one variable (the independent variable) and another variable (the dependent variable).

4. Compare what "type" means in julia with what "set" means in mathematics
A type system describes how a programming language treats individual data and determines how to use it based on its type. Julia's type system is mostly dynamic, which means you don't have to tell Julia which type is a particular value. However, In mathematics a set is a collection of distinct elements.The elements that make up a set can be any kind of things: people, letters of the alphabet, numbers, points in space, lines, other geometrical shapes, variables, or even other sets. 

5. What is a "bug"?
In computer science, a bug or boguenote 2 is a design flaw in a computer program causing a malfunction.
The severity of the malfunction can range from mild, for example causing minor display faults - in this case we will sometimes speak of "glitch (es)" - to major, such as a system crash that can lead to serious accidents, for example. the in-flight destruction of the first Ariane 5 rocket in 1996.
A bug can reside in an application, in the third-party software used by this application, or even in the firmware of a hardware component as was the case with the bug of the Pentiumnote 3 division. A patch is a piece of software intended to correct one or more bugs.

### Your learning notes of the week:
#### What was surprising? 

- *Write a topic*
- *Why?*

#### What was hard to understand? 

- *Write a topic*
- *Why?*


#### What do you need to recapitulate?

- *Write a topic*
- *Why?*


# Curriculum Course MDSP - Week 5

You have seen that mathematics is more about symbols and construction of ideas than about numbers.
Your first steps made you familiar with notation, proof, sets, and functions.

Do you know what "time" is?
Like "time", these mathematical ideas seem so simple and at the same time so complicated.
No worries, you will meet these ideas time and again!
Why?
Because these ideas go all the way when understanding mathematics.

Having understood these fundamentals, you are now ready for the first step understanding an application of these ideas: programming in the julia language.

### Note:
To master programming, you will need to practice coding, writing programs, running programs.
Thus it will be best to organize a computer to learn the programming language julia.


## Basics of programming

1. Read chapter 1-3 in [Think Julia: How to Think Like a Computer Scientist (Ben Lauwens)](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html),
2. memorize [Glossary](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html#_glossary)
3. Read [unit testing](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html#_unit_testing)
3. voluntary: read [what exactly is the semantic difference between set and type](https://cs.stackexchange.com/questions/91330/what-exactly-is-the-semantic-difference-between-set-and-type/91345?noredirect=1#comment197425_91345)

Think about these analogies between mathematical and programming terms:

- Syntax is how you write, similar to logical notation.
- There are proofs in theoretical computer science.
  In practice, programming invites a lot of "trial-and-error":
  The computer offers you to "run what you wrote", so you can test if you get what you intended.
  Logical construction is a rigorous way to determine whether a conjecture is true/false -- if someone finds a proof.
  Program construction is a faster way to make something work -- most of the time at the cost of bugs.
- Julia types are a formal way to clarify "what?" is talked about, similar to sets.
- Julia functions can transform arguments to some computation result, similar to a mathematical function from the Cartesian product of function arguments to the return type.

