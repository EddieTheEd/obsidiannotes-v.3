---
layout: default
title: "Comp Sci 3"
---
# Comp Sci 3

## Types of Error:
- **Syntax**
	- Make a typo mistake
	- e.g. write 'pint' instead of 'print'
	- 2 ways a computer detects a syntax error:
		- **Compiler**
			- Take all the code, convert to machine language and run it
			- If there is a syntax mistake, it won't be able to tell you where it is, as it converts the code all at once.
			- ADV: Faster, as it converts it all in one go.
			- DISADV: Won't tell you where mistakes are
		- **Interpreter**
			- Convert **each line** at a time.
			- If there is a mistake, it will tell you, and **which line**.
			- ADV: Tells you what the mistake is.
			- DISADV: Slower, converts lines individually
- **Logic**
	- Doesn't produce what you want to produce
	- e.g. instead of 1 + 1 you do 1 * 1
		- Program runs, but doesn't produce what you're looking for.
		- When compiled, everything will work correctly
	- To find a mistake, use **trace table**.
		- Enter the line number of the program
		- Then variables
		- Conditions such as if, while, etc. or functions ( 1 + 1)
		- Then output
		- (This is in 1 row)
		- Tells you what's logically wrong in the program.
- **Runtime**
	- Specific, as related to logic
	- Program runs, but runs in infinite loop, and crashed computer
	- e.g. **What happens when you divide by 0**


