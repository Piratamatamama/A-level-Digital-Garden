---
{"dg-publish":true,"permalink":"/ch5-operating-system/"}
---

- [[#1. Memory management|1. Memory management]]
		- [[#1. memory optimisation|1. memory optimisation]]
		- [[#2. memory organisation|2. memory organisation]]
		- [[#3. memory protection|3. memory protection]]
- [[#2. File management|2. File management]]
- [[#3.  Security management|3.  Security management]]
- [[#4. Process Management|4. Process Management]]
- [[#5. Hardware Management|5. Hardware Management]]
- [[#Utility programs:|Utility programs:]]
- [[#Library program|Library program]]
- [[#Types of Language Translator|Types of Language Translator]]
	- [[#Library program#1. Interpreter|1. Interpreter]]
	- [[#Library program#2. Compiler|2. Compiler]]
	- [[#Library program#3. Assembler|3. Assembler]]
os provide a user-interface for user to interacts with computer without needing to code
only use WIMP (window, icon, menu, pointing device)
#### 1. Memory management
###### 1. memory optimisation
- allocate memory/ ram to process
- swaps data to and from hard drive
- handles virtal memory
###### 2. memory organisation
- Keeps track of allocated and free memory locations
- Uses **paging** and **segmentation** to divide memory
- Organises memory structure for efficient access
###### 3. memory protection
- Protects memory from being accessed by the wrong process
- Ensures each process can only access its own allocated space
#### 2. File management
- maintain file directory structure
- implement access rights 
- name/ delete/ copy/ cut file
- file naming convention
#### 3.  Security management
- virus checker
- firewall
- system update
- automatic backup
- system restore
- implement access rights to different users
- sets up user accounts and check usernames, passwords(authentication)

#### 4. Process Management
- allocation of resources to process
- enable process to share information
- prevent interference between processes
- handle  priorities
- allow multi-tasking
- scheduling to decide which process to run on CPU
	1. FCFS
	2. round robin
	3. SJF
	4. SRJF
 



#### 5. Hardware Management
1. installation of device driver software
	- for computer to communicate with hardware devices
2. managing interrupts 
3. sending control signal
4. control of buffers
5. management of queues
![image-37.png](/img/user/Pics/image-37.png)

#### Utility programs:
- additional program that helps to maintain system
1. disk defragmentor
- scattered memory -> organise into contiguos blocks ->read-write head retrieves data faster because in contiguos form  

1. disk repair
- flag bad sector/ corrupted sector ->repair/ resolve error -> retrieves data from damaged disk
- hard bad sector= manufacturing error, damaged to disk surface, difficult to repair
- soft bad sector= sudden loss of power , static electricity, leads to data corruption

1. disk formatter
- partition disk into memory drives
- prepare disk for initial use
- sets up file system

1. file compression
2. virus checker
- before installing
- check against database of virus
- heuristic checking for possible activity of a program that are like a virus
- quarantine for user to decide before deleting

1. back up software
- system restore point 
- if corrupted, can return to the exact restore point
- back up to external hard drive

#### Library program
 - containe tried and tested library routine
 - libary can be imported into program
 - routine can be called by program

1. static library program
- program libray are embedded into program directly
- no need to be available at run time since library code already compiled alongside main code

1. dynamic library program
- program library linked to main code using linking software
- library need to be available at run time for code to function correctly
 |--|--|--|
### Types of Language Translator
- reason of using
- benefits
- drawbacks
##### 1. Interpreter
- use when program is still developing/writing
- to test/ debug the partially completed program
- interpreter stops as soon as it finds error, so errors can be corrected at real time 
- to change the program and see the effects of changes in real-time

- error can be corrected at real time because interpreter stops
- can run a partially finished program when still developing
- effect of changes to code can be seen in real time

- need to re-interpret everytime 
##### 2. Compiler
- use when program already finished written
- to transform program code into executable object code

- program can be distributed without source code
- compiler is not required to run the program/ not required at run time, program can run independently
- no need to re-interpret everytime the program is run
- code executes faster than interpreter

- program will not run if there is any error
- program must be recompiled after any changes made to code


##### 3. Assembler
- transform low level assembly code into machine/binary code
- 
2 pass assembler