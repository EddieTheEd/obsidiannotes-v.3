# Computer Science Exam Prep (Monolithic Document)
Here is a monolithic document that contains all of my Computer Science notes, which I made in preparation for the Semester 1 Exam.

**Some Good Links:**
- [GCSE Computer Science - BBC Bitesize](https://www.bbc.co.uk/bitesize/subjects/z34k7ty)
- Your respective OneNotes

## Computing Systems
For computing systems, there are 2 main categories that things can go into, these are:
- **Hardware**
- **Software**

From here you can go into more detail, and here is all the main course content that you need to know:

### Hardware:
- ***What is the Processing Architecture?***
	- This is a system which involves having an 'input', some form of 'processing', and then some form of 'output'. This is seen in all common computers. A simpler way of visualising this is as below:
		- **Input -> Computer/Processing -> Output**
			- ***What is an 'Input'?***
				- An input is a device/piece of hardware that gets information of some kind. 
				- *Examples of Input Devices:*
					- scanners
					- keyboard
					- mouse
					- touch-screen
					- sensors
					- etc.
				- This forms a vital part of computers, as this allows for information such as keystrokes from a keyboard, and the position of a mouse to be calculated, therefore allowing for a more user-friendly user experience
			- ***What is an 'Output'?***
				- An output is a device/piece of hardware that gets the processed information, and displays them in some form to be accessible to an end-user. 
				- *Examples of Output Devices:*
					- Monitor
					- Printer
					- Speakers
					- etc.
				- This is also a fundamental part of computers, as this provides feedback for the end user as to what they are doing. This is generally visual, although can appeal to other senses (such as through the use of Audio). 
			- ***What is 'Processing'?***
				- Processing involves the manipulation of data to produce a different result. This can be as simple as counting up/down, or keeping the time, but through more complex calculations, can do things such as physics calculations.
				- **Components of 'Processing' (2)**:
					- CPU
						- *Central Processing Unit*
						- This is the main form of processing in most computers, and has a chip that has many tiny silicon transistors
						- *Parts of a CPU:*
							- **CPU Busses (3):**
								- **Address Bus**
									- This holds information for all the addresses (i.e. where all the data is located, especially for RAM)
								- **Data Bus**
									- This bus has access to all the data in a computer, and is able to read/write to hardware
								- **Control Bus**
									- This bus controls all the other busses, and includes the Control Unit (CU), which generates instructions.
							- **CPU Components (5 Units)**
								- **Control Unit (CU)**
									- This controls all the data transfer and instructions for the CPU
									- Manages all the other units
									- Gets instructions from memory, and directs the operation of the computer
									- Communicates with input/output devices to transfer data from storage
									- **DOES NOT** process or store data
								- **Arithmetic Logic Unit (ALU)**
									- Does the actual processing of data
								- **Registers**
									- Memory Device (Information from the ALU goes to a Register)
								- **System Clock**
									- Keeps track of operations, and keeps operations in sync (the clock speed in a CPU)
								- **Program Counter**
									- Counts the tasks being done (+1 per process), and notes what the next instructions are, and what data has been processed and schedules the next operation
							- **CPU Fetch Cycle (4)**
								- **Fetch Data**
									- **Done by the Control Unit**
									- Fetches data from memory
								- **Decode**
									- **Done by the Control Unit**
									- Translates information into machine code
								- **Process**
									- **Done by the Arithmetic Logic Unit**
									- Does the actual processing of information
								- **Store**
									- Done by the Registers, and it stores information into Primary and Secondary Storage.
					- ***Memory***
						- **Primary Memory**
							- Primary Memory consists of '*Volatile*' memory (think about it as things that are generally flushed after shutting down a computer). As these are usually deleted very often, it doesn't hold any vital long term information, and generally holds temporary information (such as application details, and cache)
							- *Examples of 'Primary Memory' are:*
								- **RAM**
									- *Random Access Memory*
									- **Not directly connected to the CPU**
										- Note that this is the only example of Primary Memory that is not directly connected to the CPU
									- This is the most commonly recognisable form of primary memory, and is generally the largest capacity of Primary Memory in a system. This holds working information from the CPU (such as instructions), application details and cache
								- **Cache**
									- **Directly connected to the CPU**
									- This generally holds instructions for the CPU, especially if it is likely to reuse them. This is generally very small (in modern data standards), as it only holds information in hexadecimal or binary
								- **Registers**
									- **Directly connected to CPU**
									- This holds information about the information (such as what address information is held), and other temporary information that is vital to CPU instructions
							- **Advantages/Disadvantages of Primary Memory**
								- **Very Quick**
									- This is vital, as CPUs have gotten good enough where the Primary Memory is often a bottle-neck. Due to this, this memory has to be extremely quick in order to allow for the CPU to go to it's full potential. This also means that it is generally flash memory, as it is extremely quick, and also doesn't require any extra moving parts (and reducing points of failure is important for a CPU, which doesn't have any moving parts at all)
								- **Very Small (in Capacity)**
									- This is a downside of Primary Memory, as it is so expensive, it is difficult to get large amounts of it. It is also not designed to hold a lot of information, as it only needs to hold hexadecimal values or binary. 
						- **Secondary Memory**
							- Secondary Memory consists of more '*Permanent*' memory (i.e. things that persist after shutting a computer down). This is what more important things are generally stored (such as documents, and user files), as otherwise they would be flushed every time someone were to shut down their computer.
							- *Examples of 'Secondary Memory' are:*
								- **SSD**
									- *Solid State Drive*
									- This is a storage device that uses '*flash-storage*' (i.e. something that holds electricity to represent a bit), and is generally very quick, and the downside of being more expensive per gigabyte. SSDs have no moving parts, and therefore are very reliable
								- **HDD**
									- *Hard Drive Disk*
									- This is a storage device that uses physical 'platters', that are written into via a laser to produce bumps, which can then be read as a binary '0' or '1'. This allows for permanent storage, and is significantly cheaper than SSDs to manufacture, and have a higher gigabyte/dollar value, at the cost of being significantly slower than an SSD.
							- **Advantages/Disadvantages of Secondary Memory**
								- **Needs an Extra Controller:**
									- Secondary Memory needs an extra controller to access (i.e. the CPU cannot directly access it). It needs something such as an *'NVMe'* Controller or *'SATA'* Controller to access.
								- **Easier to package:**
									- It is connected to the Motherboard, and therefore can be much more spread out (with things such as cables allowing for much freer designs and applications)
								- **Much cheaper than Primary Memory**
									- It is significantly cheaper than Primary Memory to produce, and also has the option to be much larger than Primary Memory
								- **Much slower than Primary Memory**
									- As it isn't as vital for this memory to be quick, it is generally slower to have the potential of fitting in more information in for the money
								- **Much more storage compared to Primary Memory**
									- Secondary Memory can hold much more memory compared to Primary Memory as it is designed to hold different forms of information such as documents, and the Operating System, which take up a lot of room.

### Software:
- ***What are the different types of software?***
	- **Operating System**
		- This is a piece of Software which is the main interface that a user will interface with, and also the main framework for applications to be run
		- **Types of Operating Systems**
			- **Desktop Operating Systems**
				- Standard consumer operating systems (such as Windows, MacOS and GNU/Linux)
			- **Server Operating Systems**
				- Server operating systems (such as RedHat, CentOS, Microsoft Server OS)
			- **Embedded/Realtime Operating System**
				- Embedded Devices
				- Instant Access to information/processing
	- **Application**
		- Specific pieces of software, that perform a specific function, for a specific task.
		- **Examples of Applications**
			- Microsoft Word
			- Microsoft Excel
			- Premiere Pro
			- Blender
			- Google Chrome
			- Microsoft Store
			- etc.
	- **Utility Software**
		- Controls actual hardware, and allows for it to run smoothly
		- **Examples of Utility Software:**
			- Anti-virus software
			- UEFI/BIOS
			- Clean-Disk Software
			- Drivers
			- Firmware
			- etc.





## Databases
This will have all my notes for Databases

### Databases Notes
- **What are the components of a Database?**
	- **Table**
	- Where actual data is stored
	- ***FEILD***s represent entire columns of data
	- ***RECORD***s represent entire rows of data
	- This is a literal table (similar to what you would find in an Excel speadsheet)
	- **Form**
	- How you are able to put data into a table
	- **Query**
	- Uses SQL (Structured Query Language) to retrieve data from a database
	- **Report**
	- Outputs from a query, presented to the end user
- **What are Data Anomalies (Data Integrity)?**
	- **Insertion Errors**
		- More information is needed, as you otherwise have null values in cells
	- **Deletion Errors**
		- If you delete something, you have to delete an entire RECORD, and therefore have the potential of deleting things that you would not have wanted to delete
		- You also cannot have a null value
	- **Update Errors**
		- Potential for records to be different, as only some are updated (due to duplication of data)
- **What are the different types of 'Integrity' in a database**
	- **Entity Integrity**
		- Making sure that each Entity has an 'ID' attribute as a Primary Key
		- Check the validity of each entity
	- **Referential Integrity**
		- Having a primary key and a foreign key for every link (1:M relationships)
	- **Domain Integrity**
		- Making sure that inputted data is correct and true
		- Uses a 'Data Dictionary' to make sure inputted data is correct
			- **What is a Data Dictionary?**
| Field     | Size | Format   | Sample                | Constraint       |
| --------- | ---- | -------- | --------------------- | ---------------- |
| builderID | 5    | integer  | 10010                 | Primary Key (PK) |
| Name      | 3    | String   |                       | Required         |
| Email     | 50   | String   | 'example@example.com' | Required         |
| Expenses  | 30   | Currency |                       | Require "$"      |
| Dates     | 20   | Date     |                       |                  |
 
- **What is Normalisation?**
	- The process of separating a flat table into separate tables for each entity with relationships.

- **SQL Notes**
	- ``SELECT``: Choose a table
	- ``*,+,-,<,>``: Or other standard wildcards are valid
	- ``FROM``: Choose where the selection will take place
	- ``WHERE``: Add in constraints
	- ``;``: Signals the end of a query
	- ``AND, OR``: General operators

 **SQL Examples**

**Teachers**
 | TeacherID | Teacher Name |
| --------- | ------------ |
| 4445      | Mr Surrali   |
| 4433      | Mr Wilson    |
**Students**
| Student ID | Student Name | Gender | DOB      |
| ---------- | ------------ | ------ | -------- |
| 67678      | Jim Smith    | M      | 30/01/20 |
| 67677      | Jane Jones   | F      | 20/1/20  |
| 67222      | Lucy Kid     | F      | 8/03/20  |
**Courses**
| CourseID | Course Name           |
| -------- | --------------------- |
| F451     | Computer Fundamentals |
| F452     | Programming and Logic |
 
SQL Example Code (Find female student named Jane):
`SELECT StudentName, Gender`
`FROM Flat_Databse`
`WHERE Gender="F"`
`AND Student Name = "Jane";`

SQL Example Code (Find what subject teacherID 4445 teaches)
`SELECT Course_Name, Teacher_Name`
`FROM Teachers, Course`
`WHERE TeacherID = '4445'`

