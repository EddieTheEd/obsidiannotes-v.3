---
layout: default
title: "Comp Sci 4"
---
# Comp Sci 4

*Trace tables* are used to locate **logic errors**, while *compilers* find **syntax** or **runtime** errors (*sometimes it doesn't work :(*)

## Software Development Cycle(5 stages):

1. State the Problem
	- What is the problem, how will I fix it?
		- What program
		- What computer
		- What type of software
		- What is it?
		- What software are we developing?
		- Who is the client?
		- How will I do it?
		- What resources do I have?
		- What libraries will I use?

2. Plan and Design
	- Plan to create a program.
	- Here, pseudocode and flowcharts are used.
	- Use control stuctures:
		- Sequence
		- Selection
		- Repetition
	- Create flowchart for program (*structure chart*)
		- e.g. Main is linked to Input function, process function, and printing function.
		- The parameters of these functions move between the different modules (e.g. from main to input)
		- The main function called another function, and gives the function parameters
		- The function returns its process back to the main.

3. Develop
	- The coding of the program
	- **Internal** and **external** documentation
		- Internal documentation: 
			- **Comments!** 
			- Informs the main developers of the program.
			- Is for other developers who are trying to understand the code.
			- Is also *inside the code!*
		- External documentation: 
			- Documentation *outside* the code intended for the user.
			- How to use the program (instruction manual)
			- Function of the program
			- Anything a program could have that needs to be written down and/or distributed to the user
				- e.g. Serial number
				- *User Licence Agreement* or **EULA** (end user licence agreement)
					- Contract between the developer and the user.

4. Test
	- Use trace tables
	- Check that the program runs as intended

5. Evaluation
	- Use target audience,
	- Program is evaluated to see whether it works as intended and was designed to do.


### Trace Table Exercise 2

1. 
| Sum          | Number | Output               |
| ------------ | ------ | -------------------- |
| 0            |        |                      |
| 0            | 12     |                      |
| 0 + 12 = 12  | 12     |                      |
| 12           | 23     |                      |
| 12 + 23 = 35 | 23     |                      |
| 35           | 34     |                      |
| 35 + 34 = 69 | 34     |                      |
| 69           | 0      |                      |
| 69           | 0      | "Sum of number is69" | 

2. 
| ElementNum | Value | NumPrev | NumPrevPrev | Current | Index | Return |
| ---------- | ----- | ------- | ----------- | ------- | ----- | ------ |
| 5          | 0     |         |             |         |       |        |
| 5          | 0     | 1       |             |         |       |        |
| 5          | 0     | 1       | 1           |         |       |        |
| 5          | 0     | 1       | 1           |         | 2     |        |
| 5          | 0     | 1       | 1           | 2       | 2     |        |
| 5          | 0     | 1       | 1           | 2       | 2     |        |
| 5          | 0     | 2       | 1           | 2       | 2     |        |
| 5          | 0     | 2       | 1           | 2       | 3     |        |
| 5          | 0     | 2       | 1           | 3       | 3     |        |
| 5          | 0     | 2       | 2           | 3       | 3     |        |
| 5          | 0     | 3       | 2           | 3       | 3     |        |
| 5          | 0     | 3       | 2           | 3       | 4     |        |
| 5          | 0     | 3       | 2           | 5       | 4     |        |
| 5          | 0     | 3       | 3           | 5       | 4     |        |
| 5          | 0     | 5       | 3           | 5       | 4     |        |
| 5          | 0     | 5       | 3           | 5       | 5     |        |
| 5          | 5     | 5       | 3           | 5       | 5     |        |
| 5          | 5     | 5       | 3           | 5       | 5     | 5       |

#### Things to fix:
***MUST* put conditions in trace table!!**
**Write output!**
**Write line column!**

e.g. 
| Line | Number >=0 |
| ---- | ---------- |
| 3    | **T**           |

## Ideas for Program
- Calendar program
- Voice assistant - gui?

#### Downloaded Packages:
- Pip
- SpeechRecognition
- gTTS
- playsound
- wolframalpha
- pyttsx3
- tkinter
- webbrowser(apparently?)
- datetime
- requests
- beautifulsoup4
