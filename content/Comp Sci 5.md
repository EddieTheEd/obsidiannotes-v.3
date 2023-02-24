---
layout: default
title: "Comp Sci 5"
---
# Comp Sci 5

Plans for program:
- ~~log all communication~~
- save user data, so dont have to ask for name on start up
	- save startup routine? voice assistant follows specific instructions for startup
- add better functions
	- separate file (.py or .txt)
	- human formatting
- improve graphics
- Account system!!!
	- Account data set in .txt file
	- Python tkinter will run account setup
	- Iterate through all accounts in .txt file, will create buttons for each account
		- Each account button calls same function, with parameters of the account data username or something
	- The function called uses the parameters to find the account data, and loads it up
	- Account data can be edited and created via tkinter multi-line program
	- DICTIONARIES?????????????
- Add functions!
	- Functions can be written in tkinter multi-line program
	- written in some "human like" language
	- deciphered by code
		- Will have to consistently create different functions that will parse the given function and do specific thing
		- e.g. function for opening app "x", closing app "y", googling text and send emails will be separate function => put in separate .py file?
	- **core idea is that keywords will be interpreted as functions where numerous individual functions are run, e.g. if i say the words "start the grind", obsidian and firefox both open**
- Talk to use through open ai
- Video players... im gonna die
- POMO TIMER!!!!!!!!!!
- **==BOXSTATUS FUNCTION DESTROYS IMAGE EVERY TIME, THIS IS INEFFICIENT. CONSIDER DEBUGGING LATER. THE ISSUE OCCURS WHEN .update() IS USED, WHICH MAKES THE IMAGE BLANK. THIS MAY BE FIXED BY REDEFINING THE IMAGE???==**
- Idle stage, silently listens and when user asks for input return to main program
- configure starting position?

### Rough Plan for files

- main.py => will call setup, run code to load functions (this will be in setup), will get user data, and contain all the tkinter to do all the input and output stuff
- data.txt => where all voice communication and interpretation is logged
- functions.txt => "human language" style text file, has all the possible functions the program can do. will be unpacked by main.py so the program can run all the functions and check for errors (?) ahead of time.
- accountdata.txt => where all account data will be stored

==why doesnt highlights work==