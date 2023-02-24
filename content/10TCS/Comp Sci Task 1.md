---
layout: default
title: "Comp Sci Task 1"
enableToc: false
---

![](000_Files/Untitled%20design-modified.png)

1. State the problem

**Description**
- The core idea of the program is a voice assistant targeted for high-school students as a useful tool in managing and optimising their work/study life on the computer.
- I've titled the program **Ed's Voice Assistant**, as it is a voice assistant made by me.
- The program is a personal tool app. It is not designed to be used for educational purposes, and while it caters for improving the education quality of high-school students, it does not directly provide education. It may also be considered an entertainment app, but its primary focus is as a digital tool to improve a user's interaction with their computer.
- Once initialized, the voice assistant will listen to the user and execute a range of functions, such as opening Firefox, opening Obsidian (note-taking app), etc. There is also some quality-of-life functions for the program, such as closing the program.
- As stated before, the target audience is students, as I feel that most students could use a voice assistant in terms of managing and further optimizing their computer usage, aiming predominantly for greater ease of use. 
- I aim to create a voice assistant that will allow increased productivity when using their computer for study or work. The target audience, myself included, wish to increase their personal productivity when studying, by eliminating repetition and tediousness that occurs regularly. 
	- For example, when I am studying chemistry, I open Firefox, Obsidian and OneNote, and open textbooks I have on my computer. This takes valuable time, and reduces my overall efficiency when studying. I plan for my voice assistant to remove this inefficiency, by allowing custom commands, where if I were to say a key phrase, it would do all of these things at once, saving me crucial time.
	- In the future, I also plan for the voice assistant to be a general tool in the office, for example it could send emails to large batches of fellow colleagues. 
	- Furthermore, people who have used voice assistants before may demand high quality in graphical design of the program. Using Tkinter, I plan to provide a well-thought-out visual interface, however **I have used copyrighted images (Siri logo) for parts of the visual design**, as I feel its simplistic design fits my program, and I admire the quality of the Siri voice asssitant.
- The program will fill its user's need for a simplistic, easy-to-use voice assistant that will improve their productivity. It will also improve their quality of life, by helping its users achieve a healthy study schedule/routine.
- The licencing used is the Permissive MIT licence, the reasoning for which is explained at the end of the Licencing section.
	- Having published the project to GitHub, anyone who wishes to modify my code through GitHub will automatically follow the licencing requirements of the MIT licence. Their programs should contain the original copyright notice and a copy of the original MIT licence.

**Licencing**
Currently, there are 3 main software licences used by companies across the world:
- *Permissive*
	- **Examples:**
		- BSD licences (family)
		- MIT Licence
		- Apache Licence
		- ISC Licence
		- JSON Licence
	- Permissive licences are a kind of free-software licence, which means it is allows users to run the program the licence is attached to, analyse the code of the program, and most importantly redistribute modified version of the program under whatever licence fits. This essentially allows developers to configure a program how they see fit, and release their new program under a new licence.
	- Permissive licences are also very compatible with other licences, due to its minimal restrictions on the user.
	- *It should be noted that a crucial flaw with Permissive licences is that they do not guarantee the type of licence of derivative software, and thus can result in derivative programs that are not free or publicly available.*
	- There are a few requirements for users of a program under a permissive licence, if they wish to redistribute the software:
		- They must leave in the original copyright notice.
		- They must leave the initial licence text of the program, such as the one shown below:
```yaml {title="MIT License text"}

_Begin license text._

---

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

_End license text._

```
- *Copyleft*
	- **Examples:**
		- GNU General Public Licence
		- GNU Lesser General Public Licence
		- Mozilla Public Licence
		- Open Software Licence
		- Microsoft Reciprocal Licence
	- Copyleft licences are considered generally quite restrictive, and require that the same established rights in the license of the initial software remain in any derivate programs. However, Copyleft licences are still considered relatively open-source, as like Permissive licences, they grant many user freedoms, such as:
		- Right to perform/display, i.e. the right to use/display the program in public
		- Right to modify
		- Right to distribute
	- However, compared to Permissive licences, Copyleft licences do not allow users intending to redistribute modified software to include sublicences. In general, Copyleft licences also stipulate that redistributed version of software must keep the source code available to recipients of the new software. Furthermore, any derivative version must have the same licence as the initial software.
	- **The core difference between Copyleft and Permissive licences is that Copyleft licences require that any derivate programs contain the same licence.**
- *Commercial/Proprietary*
	- **Examples**
		- There are no examples of public licence for Proprietary and Commercial software, as in general companies create specific legal agreements between them and users.
	- Proprietary/Commercial licences are some of the most restrictive licences available for software.  Minimal amounts of users are usually given, such as rights to use and display the program. However, the use of software under Proprietary or Commercial licences are usually highly restrictive.
		- For example, Adobe licences used to be limited to one users, i.e. they could only be used on one computer at a time.
	- Commercial and Proprietary licences are generally considered *closed-source*, as most Proprietary and Commercial programs are distributed in their **compiled form**, compared to **source code**.
	- In general, Commercial and Proprietary licences also heavily restrict the redistribution of software. Where source code is available, some Proprietary and Commercial licences also restrict the distribution of modified source code.

*Having research many software licences, I have settled on using the MIT licence for my program. I believe this licence reflects my desires for the use of my program, as I hope that others can take the program and improve on it for their own use. I also believe that if their version of my voice assistant is both unique and helpful for others, that its developers should be able to relicense it.*

**Resources**
The program is Python based (Python 3.10), and relies on text files to store data. The program also requires a lot of modules for its basic function:

*Modules:*
| Module Name        | Purpose                       | Importance          |
| ------------------ | ----------------------------- | ------------------- |
| tkinter            | GUI Design                    | Essential           |
| pyttsx3            | Outputting voice              | Essential           |
| speech_recognition | Recognising user input        | Essential           |
| PIL                | Getting images                | Moderate Importance |
| atexit             | Running code when script ends | Moderate Importance |
| fileinput          | Closing text files            | Low Importance      |
| sys                | Debugging in console          | Low Importance      |
| time               | Getting time for the user log | Low Importance      |
| Open Ai            | Does cool commands for user   | Essential           | 

There is minimal equipment requirements for the creation and development of this program. I used a relatively high-end Dell XPS-15 and Visual Studio Code for the development of the software. However, I had to install Python 3.10, and also all the modules listed above through PIP installation.

For Visual Studio Code, I had the *Pylance* and *Python* modules installed. *Pylance* offers **rich type information**, i.e. gave suggestions for minor things for code, e.g. parameters, while the *Python* module allowed me to run and write the code in Visual Studio Code.

I also used multiple sources of documentation for the various libraries for the program, such as Python Tutorial's website(https://www.pythontutorial.net/tkinter/), Tkinter documentation in Python(https://docs.python.org/3/library/tk.html), the official documentation of pyttsx3(https://pyttsx3.readthedocs.io/en/latest/), etc.

In terms of skills and expertise, I have moderate skills in Python coding. I have a strong understanding of how functions work, which prove incredibly important for managing the structure of the program (having a main function, having a function that takes user voice input, having a function that speaks, etc.). Furthermore, through a strong understanding of lists, dictionaries and the use of text files in Python, I was able to store user data in a text file, and log all user interactions with the program in another file.

I decided to log the actions of the program, as I felt that this would prove quite helpful as a means of gauging errors in the. However, I did not get to be able to log the change in variables present throughout the program, which means the logs will most likely be unhelpful for fixing logic errors.

Visual Studio Code was my main source of testing for the program. Through its debugging menu (F5), I initially worked on the raw main.py file. I did so because when I pressed the Run Python File button, it did not access the text files. Later on while working on the project, I realised that I needed to open the folder the program was in, and from then I started using the Run Python File button, as it was easier to use.

I also used Stack Overflow as a source of advice in using complex/badly-designed modules, such as Tkinter. For example, I initially had a problem with creating a function which would create multiple buttons of the same function, but with different parameters. I had difficulty fixing this issue, as I found that when the program started up, all the buttons were essentially pressed once, and would be unusable after. 

```yaml {title='Button Code'}
for i in accountdata:

        button = ttk.Button(text = str(i))

        button['command'] = finduser(i)

        button.pack()
```
/* Note that the "finduser" function is a separate function.

However, after looking up this issue with Tkinter on Stack Overflow, I discovered that when Tkinter parses through the 'command' section, it interprets the brackets as calling the function, and immediately calls the function, while incorrectly parsing the function, making it un-callable by the user.

I also learnt from Stack Overflow to instead use Python's lambda functions.

```yaml {title='Improved Button Code'}
for i in accountdata:

        button = ttk.Button(text = str(i))

        button['command'] = lambda i=i: finduser(i)

        button.pack()
```

**Similar Products (samples)**
- *Alexa*
	- Amazon's Alexa excels in its compatibility with many operating systems, such iOS and Android. It also has numerous unique commands, and even includes voice commands that can change settings. I have considered using voice-activated commands to change settings, but I feel there is simply not enough settings to change, and it would be redundant. Furthermore, as the program is a python file, it is generally incompatible with most computers, considering the amount of modules it relies on.
- *Google Assistant*
	- Google Assistant's greatest quality is its voice recognition software, which is some of the best in the world. However, through Google's text-to-speech module in Python, my voice assistant should have the same recognition capabilities. Stylistically, Google Assistant has a simplistic, colourful design, which I have been inspired by. The design of Google's voice assistant focuses on user interaction, in its friendly voice and extensive utility as a general assistant. I am able to use Google's text-to-speech via its Python module
- *Siri*
	- Apple's Siri is a very versatile voice assistant. It has limited settings, and is not very compatible compared to other well-known voice assistants. However, in terms of languages available, Siri is quite compatible, supporting up to 21 languages as of April 2021. Siri is mostly designed for mobile uses, which is why it is the most popular voice assistant for mobile devices. Unfortunately, as my program is written primarily in Python, and requires a lot of Python modules, it is incompatible for mobile use. However, I hope to design a voice assistant with much more basic voice commands than Siri, and my idea of customised voice commands give my program an advantage over Siri.
2. Plan and Design

**Screen Layout**
Initial Layout:
![](000_Files/Pasted%20image%2020220912213050.png)
- I've intentionally moved it off to the corner. I feel that voice assistants should be subtle in their location, and having it stuck in the middle would be confusing and weird for the user to use. 
- I personally worked on the design for the favicon logo and the central logo for the program.
	- The design features the logo of Siri, with inverted colours, surrounded by 1 thick circle and 2 thinner circles, under a chromatic background, with a plus symbol in the bottom right corner.
		- The reasoning for the Siri logo is because Siri is a popular voice assistant, one which I am inspired by in its accessibility and ease of use.
		- I feel the chromatic background will appeal to younger audiences, as it gives a sense of modernity. In doing so, I've attempted to entice young high-school students into using my program.
		- The plus sign is found in other projects of mine, as an inside joke.
		- The circles surrounding the Siri logo add a sense of modernity and class to the logo.

Turning on the Program:
![](000_Files/Pasted%20image%2020220912213713.png)
![](000_Files/Pasted%20image%2020220912213732.png)
- Here I've decided to use 2 windows, as otherwise I would have run into issues with removing the central logo image of the initial window.
- I've included a little bit of code that **scales the height of the second window, relative to the number of accounts stored in the program**, so that the window can accommodate for as many account as can fit on the screen.

User Selected
![](000_Files/Pasted%20image%2020220912214816.png)
![](000_Files/Pasted%20image%2020220912214114.png)
- I create a function, the "boxstatus" function, specifically for changing the text of the window. It also logs the change in the "userdata.txt" file.

Main Voice Input Section
![](000_Files/Pasted%20image%2020220915213632.png)
- At this point, 2 new windows are created, one as a guide for new users on how to properly use my program, and one input box for the OpenAI API key necessary for the program to run. This is because I cannot leave my own API key in the code, due to the copyright of OpenAI's API, and thus I decided to input it. 
- The design of the new 2 windows are very minimalistic, like the original window. I've chosen to just leave the windows in their standard Tkinter design, while including the logo of the program. I did so as I feel that design is not the main focus of the program, and furthermore due to time constraints I considered it unwise to try and add more stylistic features to the windows.

**Graphics**
- The program features *very* *minimalistic* graphics. This is because I felt it would be too much of a challenge to use and improve on the basic Tkinter graphics. Furthermore, I feel the simplistic design of the logo makes up for the lack of visual dynamics and contrast in the graphical interface of the program. 
- I intended to use minimalistic graphics, as I believe that **the focus of a voice assistant should not be it's aesthetic beauty, but rather its functionality**. In using less engaging graphics, I hope that students will not be distracted by the program, and rather use the program to further improve their focus and productivity.

**User Interface**
- The user has 2 ways of interacting with the program:
	- Voice
		- The fundamental utility of the program is that one can use their voice to maximise the functionality of their computer usage. The program clearly indicates when it is listening for audio input, with the text box changing and an audio cue being played. 
		- This interface is a crucial element of the program, as it fulfils the core purpose of the software. 
	- Peripheral input (mouse)
		- For trivial things like starting the program and choosing an account, I decided to use Tkinter buttons for these things, as I felt they were not worth implementing voice commands, however for future designs of the program this should be implemented. 

**Algorithms: Flowcharts**

![](000_Files/Untitled%20Diagram.png)

![](000_Files/voice%20command%20flowchart%201.png)
![](000_Files/account%20creation%20flowchart.png)

**Algorithms: Pseudocode**
```yaml {title='Voice Command Code'}
# Note all the notequal signs are ! + = signs.
BEGIN
Exit <- "False"
# program only breaks when given voice command to
WHILE Exit != "True"
	OUTPUT("Listening")
	INPUT(command)
	# following IF-ELSE statements refers to inbuilt functions
	# note the "What would you like to do?" string is repeated, to indicate to the user the program is repeating.
	IF command == None THEN:
		OUTPUT("Failed to understand, will try again.")
		OUTPUT("What would you like to do?")
	ELIF "obsidian" IN command THEN:
		openObsidian()
		OUTPUT("What would you like to do?")
	ELIF "Firefox" IN command THEN:
		openFirefox()
		OUTPUT("What would you like to do?")
	ELIF "close" IN command THEN:
		closeProgram()
		Exit = "True"
	ELSE:
		# using OpenAI
		key <- "this is a working OpenAI key"
		answer = putThroughOpenAI(key)
		IF answer == None:
			# worst-case scenario, even OpenAi can't make sense of input 
			OUTPUT("OpenAI didn't understand.")
			OUTPUT("What would you like to do?")
		ELSE:
			OUTPUT(answer)
			OUTPUT("What would you like to do?")
END
```


```yaml {title='Account Selection Code'}
# Note all the notequal signs are ! + = signs.
BEGIN
INPUT(accountdata)
# data taken from text file and put into list
name <- None
# identifies whether no users
IF len(accountdata) == 0 THEN:
	OUTPUT("No Users Detected")
	# the following lines are the account creation code, simplified 
	INPUT(name)
	accountdata[0] = name
	OUTPUT(name)
# identifies whether only 1 user
ELIF len(accountdata) == 1 THEN:
	name = accountdata[0]
	OUTPUT(name)
# in this case there are multiple users saved
ELSE:
	answer <- "No"
	count <- 0
	# while loop will ask user whether any of the user names saved are the desired one
	WHILE answer != "Yes" OR count == len(accountdata):
		OUTPUT("Is this your name?")
		OUTPUT(accountdata[count])
		INPUT(answer)
		count = count + 1
	IF answer == "Yes" THEN:
	# due to how Python lists work, count - 1 was used
		name = accountdata(count - 1)
		OUTPUT(name)
	ELSE:
		OUTPUT("You chose none of them, let's try again.")
		answer <- "No"
		count <- 0
	# note that there is no feature to directly add an account when accounts exist, in the actual program you must log into someone else's account, and create a new one from there
END
```


```yaml {title='Account Creation Code'}
BEGIN
INPUT(accountdata)
# data taken from text file and turned into list
count <- 0
answer <- None
name <- None
# while loop so users have 3 tries inputting name via voice
WHILE count != 3:
	INPUT(nameAudio)
	# recognise.google is a function from a Python module
	answer <- recognise.google(nameAudio)
	IF answer != None THEN:
		name = answer
		count = 3
		# this is done to escape the while loop
	ELSE:
		count = count + 1
IF name == None THEN:
	INPUT(manualName)
	# this is physical input, i.e. typing it
	name = manualName
	# use of "name" variable so that manual and voice naming add to same variable
accountdata.append(name)
# adds name into text file
OUTPUT(name)
END
```

3. Test

**Trace Table for Voice Commands** (bold indicates new sample)
| audioInput               | query                  | program understood | openAIKey   | openAIInput        | openAIOutput                                                                                                         | Output                                                                                                               |
| ------------------------ | ---------------------- | ------------------ | ----------- | ------------------ | -------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **obsidian**             |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "obsidian"             |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | True               |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | openObsidian()                                                                                                       |
| **fire fox**             |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "Firefox"              |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | True               |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | openFirefox()                                                                                                        |
| **close program please** |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "close program please" |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | True               |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | closeProgram()                                                                                                       |
| **restart if you want**  |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "restart if you want"  |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | True               |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | restartProgram()                                                                                                     |
| **what is 9 times 10**   |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "what is 9 x 10"       |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | False              |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    | "valid key" |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             | "what is 9 x 10"   |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    | 90                                                                                                                   |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | 90                                                                                                                   |
| **what is porridge**     |                        |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          | "what is porridge"     |                    |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        | False              |             |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    | "valid key" |                    |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             | "what is porridge" |                                                                                                                      |                                                                                                                      |
|                          |                        |                    |             |                    | Porridge is a type of food made by boiling oats or other grains in water or milk. It is usually eaten for breakfast. |                                                                                                                      |
|                          |                        |                    |             |                    |                                                                                                                      | Porridge is a type of food made by boiling oats or other grains in water or milk. It is usually eaten for breakfast. |
 
4. Evaluate

**Survey**

I have made a brief survey for my voice assistant consisting of 6 rating questions and 4 written questions, which was sent to my fellow peers in my Computer Science class. The following is a summary of the results, obtained from a sample size of 11.

Question 1: "On a scale from one to ten, how organised are you?"
- Average: 5.64
- Comments: This average is quite shocking, and indicates that the target audience of the survey feel that they are unorganised. This could mean that they would gladly use productivity tools such as my voice assistant.

Question 2: "On a scale from one to ten, how important do you think productivity tools are?"
- Average: 8.09
- Comments: This average indicates that the target audience of the survey feel that productivity tools are rather important. This could reveal a potential gap in the productivity tool industry, considering the appalling prior results. Yet, this average is relatively low, and could indicate an apathy towards productivity tools.

Question 3: On a scale from one to ten, how busy are you, in general?"
- Average: 7.64
- Comments: This indicates that people consider themselves to be relatively busy, which could mean that they would appreciate a productivity tool such as a voice assistant.

Question 4: "On a scale of one to ten, how often do you use a voice assistant?"
- Average: 4.45
- Comments: This could mean that people are generally disinterested in using voice assistants, see them as ineffective, or that there has not yet been a voice assistant created that meets their needs.

Question 5: "On a scale from one to ten, how would you rate my program (any metric)?"
- Average: 8.6 (without outlier), 7.91 (with outlier)
- Comments: From the high average, it's clear that the survey participants liked using my program. This could be due to user bias, or from genuine appreciation of the program's utility. I had to exclude a specific outlier from the results, as it was completely stood out from the rest of the results.

Question 6: "How would you rate the quality of the program's code?"
- Average Stars: 4.45
- Comments: The survey participants were given a GitHub link to my program, and so were able to read the program's source code. Through either confusion or genuine analysis, the sample group returned a very high rating for the quality of the code, however it would be important to consider bias and the small sample size.

Question 7: "What do you like about the utility of the program?"
- Random Answer: "It's useful in that it makes certain activities more effecient"
- General Sentiment: The program is useful and has a nice aesthetic
- Comments: Despite personally thinking that the program has quite low utility, the survey participants gave quite positive comments. This could be a result of bias.

Question 8: "What do you dislike about the utility of the program?"
- Random Answer: "It can be slow and not register my voice at times."
- General Sentiment: Voice recognition is hard, the visuals could use some improvement
- Comments: I think overall the comments were quite positive. I can't quite improve voice recognition, as it is currently based of Google's voice recognition, and I probably could've made it clearer that the design was minimalist in nature.

Question 9: "Do you have any suggestions on improving the program?"
- Random Answer: "Use a better speech model perhaps?"
- General Sentiment: Get assistant to learn voices, more functionality, improve interface
- Comments: These are all good constructive suggestions. If I had more time, I would have certainly worked on these pieces of advice.

Question 10: "Have you experienced any issues using the program? If so, please list them below."
- Random Answer: "It doesn't recognise my voice"
- General Sentiment: The program is slow, it struggles recognising voice
- Comments: I suspect the slowness comes from the talking pace of the Google text-to-speech voice. This is an easy fix, and I could probably include this in some sort of settings window. As stated before, the voice recognition is out of my hands, and making something better than Google's voice recognition would be quite difficult.

Here is the link to the survey: https://forms.office.com/r/UTPS0bchCd

**Personal Evaluation**

Overall, I consider this project to be a success. As someone who has only used raw Python when programming, I felt that having to learn how modules and specifically how GUI modules such as Tkinter work was quite challenging, yet rewarding as I progressed through the task.

However, the task was quite tiring and due to time constraints, I was unable to maintain clarity and conciseness in the source code. I feel that there is quite a lot of inefficiency and redundancy in my source code, such as creating a function for specific windows, however I found this was the only solution at the time due to issues encountered with Tkinter.

I think that while the voice assistant is relatively quite functional, in that it can in fact open specific programs and answer intrinsic questions through OpenAI, due to time constraints I was unable to implement custom functions, which was the main goal of the program. However, the inclusion of OpenAI does make up for this lack of features, as OpenAI's API is quite powerful, and can answer very hard questions such as "What are 3 important things to remember when studying organic chemistry" with responses such as:

```yaml {title='OpenAI Response'}
1. Organic chemistry is the study of the structure, properties, and reactivity of organic compounds.
2. Organic compounds are molecules that contain carbon atoms.
3. Carbon atoms can form bonds with other carbon atoms, as well as with atoms of other elements.
```

This detail in responses from OpenAI makes up for some of the lack of functionality, however I do consider my endeavours in creating a voice assistant with substantial utility not as successful as I had hoped.

Furthermore, the following are some limitations I've derived from my program:
- No custom commands
- Account interface is quite redundant, and falls short of my idea to keep user-specific data stored.
- OpenAI is necessary when it should be voluntary
- Very little amount of actual features
- For some reason the text boxes don't align even though its in their code, this is a trivial issue
- No settings window

However, there are also some good quality of the program:
- Minimalistic design
- Can open Obsidian
- Can open Firefox
- Can answer questions through OpenAI
- Has an account system
- Saves user data in text file

In summary, I feel that my project was a great effort in working in the shoes of greater voice assistants which were developed with a lot more funding(and incentive). As a result of time constraints, I fell short of the ultimate goal of a successful, well-designed voice assistant, yet the end product has a lot of potential and could be developed into a very user-friendly, intuitive program.