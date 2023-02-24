# System Analysis

SDLC (System development life cycle):

- "Waterfall"

- "Cascade"

- "Linear"
  
  CASE tool: (Computer Aid Software Engineering)
  
  - Context diagram (CD)
  
  - Data flow diagram (DFD)
  
  - Pert chart 
  
  - Gantt chart (like a timeline)

- 

- Tasks are done sequentially (one after the other)
  
  - e.g. after task one is executed, task 2 is run, and it continues on and on.

- Used in larger projects

- Have a number of steps that you have to execute:
  
  - e.g. making the bed, eating breakfast, etc.

- Six Main stages:
  
  1. Pre-analysis
     
     - "What is the problem?"
     
     - "What situation do I have to solve?"
     
     - Make an analysis of the situation, and what the potential options are.
     
     - Different steps:
       
       - Feasability Study (F.S.)
         
         - "Is it cost effective?"
         
         - "Is it worth doing?"
       
       - Define the Problem
         
         - "What is the problem?"
  
  2. Analysis
     
     - "What do you have to do?"
     
     - With the analysis break up into potential steps
     
     - Different Steps:
       
       - Model the "current system"
       
       - Requirements of the new system
  
  3. Design
     
     - "How can you solve the situation?"
     
     - Different Steps:
       
       - Logical Design
         
         - How does it work?
         
         - What do I need?
         
         - Specificatons?
         
         - Algorithms
         
         - pseudo-code
         
         - flow-charts
       
       - Physical Design
         
         - How does it look?
         
         - Where is it going to be stored?
         
         - actual code
     
     - Use context diagram 
     
     - Use Data Flow diagram
  
  4. Develop
     
     - "What steps can I take to solve the issue?"
     
     - Steps taken:
       
       - Physical construction
       
       - Purchase hardware and software
  
  5. Implement
     
     - "This is how I will takle this?"
     
     - Steps taken:
       
       - Direct cut
         
         - Wasn't anything before, and you introduce something (new, and first time)
         
         - Introduced all at once
       
       - Phase
         
         - New system is '*phased*' in, which repaces the older hardware/system
       
       - Pilot
         
         - Continually have new systems
           
           - Introduced bit by bit (once one has been implemented, implement new ones)
       
       - Parallel
         
         - Not replacing the older systems (using the new system in parallel to the old system)
  
  6. Evaluation/Maintenaince
     
     - Take information (through something like survey)
     
     - Maintain the new system

RAD (Rapid Application Development):

- Keeps cycling, until the result is satisfied (such as epochs in Machine Learning)

- Used mostly in smaller projeNcts

- flexible

- organic

- allows for movement

- can waste time and money

**Context Diagrams:**

- It is a data flow digram, with only one massive central process, subsumes everything inside of the scope of the system

- Represents how the system will recieve and send data flows to external entities involved.

Symbols:

- **Circle**: system is represented as a cirlce (what is processing it?)

- **Curved arrow**: data flow (where is the information going?)

- **Square/rectangle**: entities (such as customers)

**DFD** (Gane & Sarson): (**Not used**)

- rounded square: process

- straight arrow: data fow

- open ended retangle with a line through it: data store

- Source/Sink (external entitiy)

**DFD symbols** (DeMarco and Yourdon) **The one we will be using:**

- **Circle:** Process (has to have the word system), otherwise it could look like a process

- Straight arrow: data flow

- = : data store

- square: data source/sink (external entities)

**Rules:**

- Have to have a data input into the process

- Data has to be manipulated by the process

- Data has to be outputted

- Can't have '*miracles*' (i.e. data that isn't being inputed, while having outputs)

- Can't have '*black-holes*' (i.e. data going in and not going out)

- Can't have '*grey-holes*' (i.e. manipulation of data is incorrect)

- Have to have processes (can't not use one)

**Level-0 DFD:**

- Shows the system's major processes, data flows, and data stores at a high level of abstraction

- After that you are able to go deeper into the system (where you go into 1.1, 1.2, 1.3, 1.4, etc.)

- Can be subdivided further (1.1.1, 1.1.2, 1.2.1, etc.)

- When the context diagram is expanded into DFD level-0, all the connections that flow into and out of process 0 needs to be retained.

Case:

1. Context Diagram

2. DFD (Level-0)

3. DFD (Level-1)

4. DFD (Level-2)

5. ... continues to DFD (Level-5)

Internal Data Flow:

- What happens within the system (between processes, databases, etc.)

External Data Flow:

- Things going into the data-flow and going out of the data flow

What is a balanced DFD? (First question in exam)

Level 1 Diagrams:

- Shows all processes (into a single process in the level 0 diagram)

- Shoes how information moves from and to to each of these processes

- etc.
