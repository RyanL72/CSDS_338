### Description
---
CFS aims to provide fair CPU time to processes while efficiently handling multitasking. 

### Key Features
---
- Maintains a [[Unix-like virtual runtime]] for each process.
- Each `CPU` has its own [[Runqueues]]. Managed by a `red-black` tree.
- Designed to ensure fair distribution of CPU time amount processes.