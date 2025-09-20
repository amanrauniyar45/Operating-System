# Operating-System Lab Assignment 1
## Topic: Process Creation and Management Using Python OS Module  
---
## Course Details
**Course Code & Name:** ENCS351 Operating System  
**Program:** B.Tech CSE "CORE"  
---
## Project Overview 
### This project simulates Linux process management using Python. It replicates key operating system behaviors such as process creation, command execution, zombie/orphan process scenarios, process inspection via /proc, and process prioritization with nice values.
---
## Assignment Objectives
*Understand Linux process lifecycle and management.
* Create child processes and execute system commands programmatically.
* Simulate and observe zombie and orphan processes.
* Inspect and extract process information from the /proc filesystem.
* Demonstrate the impact of process priority on scheduling.
---
## Tasks Implemented
**1.Process Creation Utility
** Creates N child processes using os.fork(). Each child prints its PID and parent PID, followed by a custom message. The parent waits for all children to finish.

