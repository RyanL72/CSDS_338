### Description
---
A process of creating a new process using the `fork()` system call. It spawns a `child process` from a `parent process`. 

### Code 
---
```c
pid_t pid = fork();
```

##### Returns
- `0` in the `child process` so that the process knows it's the child.
- `positive PID` to the `parent ` so that it knows the PID of its new child. 
- `-1` if there was an error in creating the child process.

- [[fork]]
- [[pthread_create]]