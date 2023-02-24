---
layout: default
title: "Comp Sci 1"
---
# Comp Sci 1

Algorithms have a **control structure**.

There are 3 kinds of control structures: 
- Sequence
	- Goes from start to finish
	- e.g.
- Selection
	- There are 3 kinds of selection control structures:
		- Single (IF)
		- Double (IF, ELSE)
		- Multiple (IF, ELIF, ELIF, ELSE)
			- CASE
			- NESTED
- Loops/Iteration/Replication/Repetition
	- While loop -> We call *first test* - **condition** of program is tested at **beginning of program**
	- FOR
		- FIX(ed)
			- Not necessary?

	- RETURN UNTIL -> Test last - program runs at least one time.

How to write control structure:
- Flow chart
	- Visual idea of how the program move
		- Oval - Begin/End of program
		- Parallelogram - Input/Output
		- Square - Process: this is where things are done with the input
		- Kite - condition, if etc.
		- Line - link between these different options
		- **DONT USE X, Y and Z AS VARIABLES**
		- Constant does not change in the code.
- Pseudocode


## Review stuff I wrote in Notepad

modules:
- separate a block of code into a specific function
- separate a program into blocks, blocks do something specific

e.g say we have a module that calculates wace
then module that calculates time elapsed
and another module that calculate tax

you use pseudocode for this!

main module: lets call it salary
in this module we need the name of person, employer, branch of work
{
call calculate wage
call cdalculate overtime
call calculate tasx
{

benefit of this is that you can call functions multiple times, so that you can repeatedly do specific tasks

ANOTHER BENEFIT is that MULTIPLE PROGRAMERS can work on SEPARATE PROGRAMS!!!!!

you have people working on specific module, and then one person working on the main moduile

this allows MORE ORGANISATION

INSIDE THE MODULE:
- local variables: ONLY WORK IN THE SPECIFIC MODULE, e.g. if we have local variable "hours", in module overtime, it ONLY WORKS IN THE MODULE OVERTIME
- global variables can work anywhere, e.g. we have GLOBAL variable "hours", it will work in any module
- PARAMETERS: 
	- next to the name of the module/function
	- like a global variable, but refers to the variable given when calling the function

MAIN IDEA: 
- DIVIDE PROGRAM INTO BLOCK OF CODE
- EACH BLOCK DOES SOMETHING SPECIFIC
- THEN THEY ARE CALLED IN A MAIN FUNCTION

Advantages vs Disadvantages:
- You don't have to rewrite a specific module, and if you have one module broken, the rest of the modules will still work, so you just have to fix one rather than all of them
- Much quicker to produce code like this
- Allows teamwork

TO SEE THESE MODULES:
We use a "structure chart"

you see main module in block, then you have it connected to other blocks
arrow connected to circle, indicates input/output flow

WHAT IS THE OPPOSITE TO VARIABLE:

a Constant!!! A 'variable' that DOESN'T CHANGE

constants could be created before a program

e.g. anyone paying over 100 gets 5% discount

this 5% is now a constant

constants and variables use different types of DATA TYPES
- string
	- text
- integer
	- a whole number
- float/real (ALTERNATIVE NAME)
	- a decimal number
- boolean
	- True/False, yes/no
- character
	- single symbol

COMPLEX DATA TYPES:
- arrays
	- a list of data of THE SAME TYPE
	-e.g. only 'a', 'b', 'c', or '453,'345345','34534', cant have '43', '19.12423'

BINARY:

source code: code created in a PROGRAMMING LANGUAGE, i.e. something a human could understand

once the source code is done, it is converted to machine code.
- we cannot understand this code, only machines can understand

BUT there is a code IN BETWEEN the machine and source code

this code is for virtual machines, and is called BYTE CODE.

e.g. convert 32 to binary
32/2 = 16 -> 0
16/2 = 8 -> 0
8/2 = 4 -> 0
4/2 = 2 -> 0
2/2 = 1 -> 0
1/2 ->1

therefore 32 in binary is 100000 (start from the end)

FIRST QUESTION OF THE TEST:
- control structures
- 3 control structures: sequence, selection, repetition

sequence:
- most basic thing, every pseudocode has sequence indicated by begin and end

selection:
- 3 types: single, double, multiple
	- single: IF
	- double: IF, ELSE
	-multiple has 2 types:
		-nested if, i.e. IF, ELIF, ELIF, ELSE
		- CASE


repetition:
- 3 types: while, for, repeat until
	- while: tests from the start, which is why its called FIRST TEST. this means the condition is tested at the end of the program
		- the program may not even run, if the condition is not even met
	- for loop has things:
		- FIX: amount of repetitions known by the program, e.g. for range(5)
			- e.g. if you get password wrong 3 times, you are locked out. in this situation, it would be better to use for loop.
	- repeat until: test from the end, which is why its called the LAST/END TEST.
		- the program runs AT LEAST ONE

REMEMBER THE SYMBOLS!!!!!!!!!!

also, ERRORS!!!
Types of Errors:
- Syntax
- Runtime
- Logic

Runtime: the program works, but doesn't work as intended, so its essentially a logic error. but in this case, you dont have time to stop it, and you produce a crash. e.g. you get an infinite loop.
Logic: you put in an incorrect logic?/function?
Syntax: when you don't type it right, the program WILL NOT WORK.
	- depending on the type of program, the programming language will identify errors differently.

2 types of ways: Compiler and interpreter

BOTH CONVERT SOURCE CODE TO MACHINE CODE

- interpreter converts line by line
- compiler converts it all

compiler is much faster, as its not going line by line. HOWEVER, AS IT DOES IT ALL AT THE SAME TIME, IT CANT IDENTIFY WHERE OR WHAT THE ERROR IS.

for interpreters, as its going line by line, it will tell you where errors are, which line they are, and what type.

THEY CANNOT IDENTIFY LOGIC ERRORS, AND GENERALLY CANNOT FIND RUNTIME ERRORS (unless it just straight up crashes)


HOW TO IDENTIFY LOGIC ERRORS:
- trace table

there are two types of trace tables:
- condensed
- extend


![](000_Files/structure%20chart.png)

