### Description
---
Used to influence the `scheduling priority` of a process. 

### Code 
---
```bash
nice -<nice> <pid>
```

```bash
nice -19 1234
```
### Key Features
---
- `+` values means lower priority
- `-` values mean higher priority.
- All `processes` start with a `nice` of 0.
- Range for the nice values are 
	- `-20` Highest priority
	- `19` Lowest priority
- Use cases 
	- Start a process with a nice value [[nice]]
	- Modify an existing process's nice value [[renice]]