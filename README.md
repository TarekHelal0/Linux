1. Overview
Simulates a CPU scheduling system
Built using C on Linux
Demonstrates real OS concepts:
Process states (Ready, Running, Blocked)
Scheduling decisions
Resource management
      - Based on OS fundamentals described in the project (process lifecycle & scheduler role)
2. Features
Supports multiple scheduling algorithms:
Highest Priority First (HPF)
Shortest Remaining Time Next (SRTN)
Round Robin (RR)
Dynamic process handling (arrival time simulation)
Process state tracking and transitions
Performance evaluation metrics:
CPU utilization
Average waiting time
Weighted turnaround time
Logging system:
Scheduler.log
Scheduler.perf
3. System Architecture
Explain components:
Process Generator
Reads input and creates processes
Scheduler
Core logic for scheduling decisions
Clock Module
Simulates system time
Process Module
Simulates CPU-bound execution

  - These components interact using IPC as shown in the system diagram (page 2)

4. Scheduling Algorithms
HPF (Highest Priority First) → executes highest priority processes first
SRTN (Shortest Remaining Time Next) → selects process with shortest remaining time
RR (Round Robin) → time-sliced execution
