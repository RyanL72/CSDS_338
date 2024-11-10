### Description
---
Dynamically adjusts a process's priority based on its behavior and CPU usage over time.


Has several `queues`, each with a different `priority level`.  Processes in `higher priority queues` are scheduled earlier.

It also has a `feedback mechanism`, which allows processes to change queues based on its `behavior`.
### Key Features
---
- Effective for systems with diverse workloads
- `CPU-bound processes` (use a lot of CPU time) are moved to lower-priority queues.
- `I/O processes` are in higher level queues.