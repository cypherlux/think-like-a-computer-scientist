# Chapter 1 - General Introduction

## 1.1. The Way of the Program

Computer Scientists combine many different ways of thinking:
- _Mathmatics_ - use formal languages to denote ideas (specifically computations)
- _Engineering_ - design things, assembling compontents into systems and evaluating tradeoffs among alternative
- _Science_ - observe the behavior of complex systems, form hypotheses, and test predictions

__Problem Solving__ = ability to formulate problems, think creativity about solutions, and express a solution clearly and accurately.

## 1.2. Algorithms

_Algorithms_ are:
- SOLUTIONS
- a step-by-step list of instructions that if followed exactly will solve the problem under consideration

>Algorithms are like recipes: they must be followed exactly, they must be clear and unambiguous, and they must end.

Define problem -> design algorithm -> create and execute the solution

>Programming is a skill that allows a computer scientist to take an algorithm and represent it in a notation (a program) that can be followed by a computer.

Computers are used to automate solutions to problems WAY more faster and accurately compared to a human doing it by hand.

## 1.3. The Python Programming Language

Python is a __high-level__ programming language.

_High-level_ programming languages:
- take less time to write
- shorter and easier to read
- are __portable__ and can run on different kinds of computers

_Low-level_ programming languages:
- aka machine lanauges or assembly languages
- encode in binary so they can be __directly executed by the computer__

Two kinds of programs process high-level languages into low-level languages:
1) Interpreters
- executes the program directly
- processed a little at a time

2) Compilers
- reads program (source code) and translates it completely BEFORE it runs

Source Code is another name for...the instructions in a program, stored in a file.

It is high-level if the program must be processed before it can run, and low-level if the computer can execute it without additional processing.

A compiler is like translating the entire book while an interpreter is like translating a line at a time.


## 1.4. Executing Python in this Book

The _activecode_ interpreter allows you to:
- save programs and reload saved programs
- type in Python source code
- execute Python code right in the text itself within the web browser

_Codelens_ allows you to:
- control the step by step execution of a program
- execute the Python code that is in codelens

## 1.5. More About Programs

A _program_ is a sequence of instructions that specifices how to perform a computer.

__Input__ - get data from the keyboard, a file, or some other device.
__Output__ - display data on the screen or send data to a file or other device.
__Math and Logic__ - perform basic mathematical operations like addition and multiplication and logical operations like `and`, `or`, and `not`.
__Conditional execution__ - check for certain conditions and execute the appropriate sequence of statements.
__Repetition__ - perform some action repeatedly, usually with some variation.

## 1.6. What is Debugging?

__Bugs__ - programming errors
__Debugging__ - process of tracking down bugs and correcting them

## 1.7. Syntax errors

__Syntax__ - the structure of a program and the rules about that structure.
__Syntax error__ - an error in the syntax or structure of the program.

## 1.8. Runtime Errors

__Runtime error__ - errors that do not appear until the program is run; also called __exceptions__ because they usualy indicate that something exceptional (and bad) has happened.

The _interpretor_ typically finds runtime errors.

## 1.9. Semantic Errors

__Semantic Error__ - when the _meaning_ (its semantics) of the program is wrong. The program will still run, but it won't do what you meant for it to do.

## 1.10. Experimental Debugging

Debugging is like detective work!

Debugging is also like an experimental science--getting an idea of what is going wrong, modifying the program, and trying again.

Programming and debugging go hand-in-hand. Programming is the process of gradually debugging a program until it does what you want. I.e., starting with a program that does something and making small modifications, debugging them as you go, so that you always have a working program.

## 1.11. Formal and Natural Languages

__Natural languages__ - languages that people speak (ex: English or Spanish) that evolved naturally over time.

__Formal languages__ - lagnauges that are _designed_ by people for specific applications (ex: math and programming)

Formal languages have strict rules about syntax, which come in two flavors:
1) __Tokens__ - basical elements of the language, such as words, numbers, and chemcal elements.
2) __Structure__ - the way the tokens are arranged.

__Parsing__ - process of figuring out the structure of something

Differences between natural and formal languages:
- __Ambiguity__ - natural languages are full of ambiguity (having multiple meanings), formal langauges are designed to be nearly unambiguous (a statement only has one meaning).
- __Redundancy__ - natural lanagues are often verbose to account for their ambiguity, formal languages are more concise and don't need fluff.
- __Literalness__ - formal languages mean what they say; natural languages are full of idioms and metaphor.

People who grew up speaking a natural language (aka everyyyyone), often have a hard time adjusting to formal languages.

## 1.12. A Typical First Program

`print("Hello, World!")`

>Hello, World!

## 1.13. Comments

Adding comments in natural language to the program help explain what the code does.
`print("Hello, World!")     # horray I'm a comment!`

## 1.14. Glossary

__activecode__ - A unique interpreter environment that allows Python to be executed from within a web browser.

__algorithm__ - A general step by step process for solving a problem.

__bug__ - An error in a program.

__byte code__ - An intermediate language between source code and object code. Many modern languages first compile source code into byte code and then interpret the byte code with a program called a virtual machine.

__codelens__ - An interactive environment that allows the user to control the step by step execution of a Python program

__comment__ - Information in a program that is meant for other programmers (or anyone reading the source code) and has no effect on the execution of the program.

__compile__ - To translate a program written in a high-level language into a low-level language all at once, in preparation for later execution.

__debugging__ - The process of finding and removing any of the three kinds of programming errors.

__exception__ - Another name for a runtime error.

__executable__ - Another name for object code that is ready to be executed.

__formal language__ - Any one of the languages that people have designed for specific purposes, such as representing mathematical ideas or computer programs; all programming languages are formal languages.

__high-level language__ - A programming language like Python that is designed to be easy for humans to read and write.

__interpret__ - To execute a program in a high-level language by translating it one line at a time.

__low-level language__ - A programming language that is designed to be easy for a computer to execute; also called machine language or assembly language.

__natural language__ - Any one of the languages that people speak that evolved naturally.

__object code__ - The output of the compiler after it translates the program.

__parse__ - To examine a program and analyze the syntactic structure.

__portability__ - A property of a program that can run on more than one kind of computer.

__print function__ - A function used in a program or script that causes the Python interpreter to display a value on its output device.

__problem solving__ - The process of formulating a problem, finding a solution, and expressing the solution.

__program__ - A sequence of instructions that specifies to a computer actions and computations to be performed.

__programming language__ - A formal notation for representing solutions.

__Python shell__ - An interactive user interface to the Python interpreter. The user of a Python shell types commands at the prompt (>>>), and presses the return key to send these commands immediately to the interpreter for processing.

__runtime error__ - An error that does not occur until the program has started to execute but that prevents the program from continuing.

__semantic error__ - An error in a program that makes it do something other than what the programmer intended.

__semantics__ - The meaning of a program.

__shell mode__ - A style of using Python where we type expressions at the command prompt, and the results are shown immediately. Contrast with source code, and see the entry under Python shell.

__source code__ - A program, stored in a file, in a high-level language before being compiled or interpreted.

__syntax__ - The structure of a program.

__syntax error__ - An error in a program that makes it impossible to parse — and therefore impossible to interpret.

__token__ - One of the basic elements of the syntactic structure of a program, analogous to a word in a natural language.


## 1.15. Exercises
