### Description
---
The current state of a process.
### States
---
- [[new]]
- [[ready]]
- [[running]]
- [[waiting]] 
- [[terminated]]

###  Diagram
---
```mermaid
graph TD
    New --admitted--> Ready
    Ready --scheduler dispatch--> Running
    Running --I/O or event wait--> Waiting
    Waiting--I/O or event completion--> Ready
    Running --exit--> Terminated

```

### Key Features
---
- Managed by [[Schedulers]]